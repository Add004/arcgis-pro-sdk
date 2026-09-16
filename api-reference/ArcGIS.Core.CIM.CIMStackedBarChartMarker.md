# CIMStackedBarChartMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Represents a stacked bar chart marker which is a chart made of vertical stacked bars displaying values.</p>


## Object Signature

```csharp
public class CIMStackedBarChartMarker : CIMChartMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStackedBarChartMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Represents a stacked bar chart marker which is a chart made of vertical stacked bars displaying values.</p>


```csharp
public CIMStackedBarChartMarker()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStackedBarChartMarker.</p>


```csharp
public CIMStackedBarChartMarker Clone()
```
### FixedLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this chart is a fixed length.</p>


```csharp
public bool FixedLength { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMStackedBarChartMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMStackedBarChartMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### OutlineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets the outline symbol.</p>


```csharp
public CIMLineSymbol OutlineSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOutline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show the outline symbol.</p>


```csharp
public bool ShowOutline { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStackedBarChartMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalBar

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this chart has a vertical bar.</p>


```csharp
public bool VerticalBar { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStackedBarChartMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


