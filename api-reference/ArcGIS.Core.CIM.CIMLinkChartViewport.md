# CIMLinkChartViewport

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Represents the link chart viewport.</p>


## Object Signature

```csharp
public class CIMLinkChartViewport : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartViewport()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Represents the link chart viewport.</p>


```csharp
public CIMLinkChartViewport()
```
### CenterX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Gets or sets the center X coordinate in the world coordinate system.</p>


```csharp
public double CenterX { get; set; }
```
### CenterY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Gets or sets the center Y coordinate in the world coordinate system.</p>


```csharp
public double CenterY { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartViewport.</p>


```csharp
public CIMLinkChartViewport Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartViewport with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartViewport FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartViewport and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZoomLevel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartViewport.yml" sourcestartlinenumber="1">Gets or sets the zoom level.</p>


```csharp
public double ZoomLevel { get; set; }
```


