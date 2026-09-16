# CIMMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Represents media info.</p>


## Object Signature

```csharp
public abstract class CIMMediaInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Represents media info.</p>


```csharp
protected CIMMediaInfo()
```
### Column

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the column.</p>


```csharp
public int Column { get; set; }
```
### ColumnSpan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the column span.</p>


```csharp
public int ColumnSpan { get; set; }
```
### IsCarousel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is a carousel element.</p>


```csharp
[Obsolete("IsCarousel is deprecated at 3.2. This property is obsolete.")]
public bool IsCarousel { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RefreshRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the amount of time in RefreshRateUnit to wait between refreshing the media info.</p>


```csharp
public double RefreshRate { get; set; }
```
### RefreshRateUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the units for the amount of time to wait between refreshing the media.</p>


```csharp
public esriTimeUnits RefreshRateUnit { get; set; }
```
### Row

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the row.</p>


```csharp
public int Row { get; set; }
```
### RowSpan

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the row span.</p>


```csharp
public int RowSpan { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


