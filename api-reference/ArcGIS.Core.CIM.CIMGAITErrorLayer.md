# CIMGAITErrorLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Represents Geospatial Analysis Integrity Tool (GAIT) datasets as a layer and draws its errors,
exceptions, and areas in need of validation.</p>


## Object Signature

```csharp
public class CIMGAITErrorLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGAITErrorLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Represents Geospatial Analysis Integrity Tool (GAIT) datasets as a layer and draws its errors,
exceptions, and areas in need of validation.</p>


```csharp
public CIMGAITErrorLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGAITErrorLayer.</p>


```csharp
public CIMGAITErrorLayer Clone()
```
### ErrorWorkspaceConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMWorkspaceConnection ErrorWorkspaceConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGAITErrorLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGAITErrorLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the line layer in the GAIT Error layer.</p>


```csharp
public string LineLayer { get; set; }
```
### PointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the point layer in the GAIT Error layer.</p>


```csharp
public string PointLayer { get; set; }
```
### PolygonLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the polygon layer in the GAIT Error layer.</p>


```csharp
public string PolygonLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Gets or sets the source feature Layers.</p>


```csharp
public string[] SourceLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGAITErrorLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAITErrorLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


