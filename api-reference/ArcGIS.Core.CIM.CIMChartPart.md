# CIMChartPart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Represents a chart part, individual components of the chart marker.</p>


## Object Signature

```csharp
public class CIMChartPart : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartPart()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Represents a chart part, individual components of the chart marker.</p>


```csharp
public CIMChartPart()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartPart.</p>


```csharp
public CIMChartPart Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Reconstructs the CIMChartPart with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartPart FromJson(string json, JsonDeserializationSettings settings = null)
```
### PolygonSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Gets or sets the polygon symbol used to draw the chart part.</p>


```csharp
public CIMPolygonSymbol PolygonSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartPart and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Gets or sets the value of the chart part used to size the part.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPart.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


