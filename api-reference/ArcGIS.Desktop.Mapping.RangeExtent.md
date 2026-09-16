# RangeExtent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Represents an extent defined by a min and a max value.</p>


## Object Signature

```csharp
public class RangeExtent
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">RangeExtent contains two properties <xref href="ArcGIS.Desktop.Mapping.RangeExtent.Min" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.RangeExtent.Max" data-throw-if-not-resolved="false"></xref> which defines an extent. Either property can be set to null. When <xref href="ArcGIS.Desktop.Mapping.RangeExtent.Min" data-throw-if-not-resolved="false"></xref> is null it means the
range extent begins infinitely small and when <xref href="ArcGIS.Desktop.Mapping.RangeExtent.Max" data-throw-if-not-resolved="false"></xref> is null this means it ends infinitely large. This is useful for example when setting
the <xref href="ArcGIS.Desktop.Mapping.MapView.Range" data-throw-if-not-resolved="false"></xref> property to show all values smaller than a given number, all values larger than a given number or to just show all values.</p>


## Members

### RangeExtent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Initialize a new instance of a RangeExtent.</p>


```csharp
public RangeExtent()
```
### RangeExtent(double?, double?)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Initialize a new instance of a RangeExtent using a min and max value.</p>


```csharp
public RangeExtent(double? min, double? max)
```
### RangeExtent(double?, double?, RangeRelation, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Initialize a new instance of a RangeExtent using a min and max value.</p>


```csharp
public RangeExtent(double? min, double? max, RangeRelation relation, bool exclusion)
```
### RangeExtent(double?, double?, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Initialize a new instance of a RangeExtent using a min and max value.</p>


```csharp
public RangeExtent(double? min, double? max, bool exclusion)
```
### Equals(RangeExtent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Determines whether the specified RangeExtent is equivalent to the current RangeExtent.</p>


```csharp
public bool Equals(RangeExtent range)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Determines whether the specified RangeExtent is equivalent to the current RangeExtent.</p>


```csharp
public override bool Equals(object obj)
```
### ExcludeMax

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Gets or sets whether values equal to the max value are considered matches.</p>


```csharp
public bool ExcludeMax { get; set; }
```
### ExcludeMin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Gets or sets whether values equal to the min value are considered matches.</p>


```csharp
public bool ExcludeMin { get; set; }
```
### Exclusion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Gets or sets whether values within the range are included or excluded.</p>


```csharp
public bool Exclusion { get; set; }
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### Intersects(RangeExtent)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Checks if this instance intersects the specified range extent.</p>


```csharp
public bool Intersects(RangeExtent rangeExtent)
```
### Intersects(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Checks if this instance intersects the specified range value.</p>


```csharp
public bool Intersects(double rangeValue)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Gets or sets the max range value.</p>


```csharp
public double? Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Gets or sets the min range value.</p>


```csharp
public double? Min { get; set; }
```
### Offset(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeExtent.yml" sourcestartlinenumber="1">Returns a new range extent offset from the current instance using the specified delta.</p>


```csharp
public RangeExtent Offset(double delta)
```


