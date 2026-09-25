# CIMBarChartMarker

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Represents a bar chart marker, a chart made of vertical bars displaying values.</p>


## Object Signature

```csharp
public class CIMBarChartMarker : CIMChartMarker, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBarChartMarker()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Represents a bar chart marker, a chart made of vertical bars displaying values.</p>


```csharp
public CIMBarChartMarker()
```
### AxesSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets the axes symbol.</p>


```csharp
public CIMLineSymbol AxesSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBarChartMarker.</p>


```csharp
public CIMBarChartMarker Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Reconstructs the CIMBarChartMarker with a specified state from a JSON encoding.</p>


```csharp
public static CIMBarChartMarker FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowAxes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show the axes symbol.</p>


```csharp
public bool ShowAxes { get; set; }
```
### Spacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets the spacing.</p>


```csharp
public double Spacing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBarChartMarker and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalBars

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this bar chart marker has vertical bars.</p>


```csharp
public bool VerticalBars { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBarChartMarker.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


