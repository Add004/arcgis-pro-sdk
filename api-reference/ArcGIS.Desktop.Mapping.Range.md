# Range

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Range.yml" sourcestartlinenumber="1">Represents a range of values defined by a min and a max.</p>


## Object Signature

```csharp
public class Range
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Range.yml" sourcestartlinenumber="1">Range contains two properties <xref href="ArcGIS.Desktop.Mapping.Range.Min" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.Range.Max" data-throw-if-not-resolved="false"></xref> which defines the range of values. Either property can be set to null.
When <xref href="ArcGIS.Desktop.Mapping.Range.Min" data-throw-if-not-resolved="false"></xref> is null it means the range has no lower bound or the range is less than or equal to the <xref href="ArcGIS.Desktop.Mapping.Range.Max" data-throw-if-not-resolved="false"></xref>.
When <xref href="ArcGIS.Desktop.Mapping.Range.Max" data-throw-if-not-resolved="false"></xref> is null it means the range has no upper bound or the range is greater than or equal to the <xref href="ArcGIS.Desktop.Mapping.Range.Min" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Range()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Range.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.Range" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Range()
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Range.yml" sourcestartlinenumber="1">Gets or sets the max value for the range.</p>


```csharp
public double? Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Range.yml" sourcestartlinenumber="1">Gets or sets the min value for the range.</p>


```csharp
public double? Min { get; set; }
```


