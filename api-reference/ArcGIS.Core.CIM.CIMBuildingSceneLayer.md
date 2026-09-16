# CIMBuildingSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Represents a building composite scene layer.</p>


## Object Signature

```csharp
public class CIMBuildingSceneLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBuildingSceneLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Represents a building composite scene layer.</p>


```csharp
public CIMBuildingSceneLayer()
```
### ActiveFilterID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the ID of the filter currently used for rendering.</p>


```csharp
public string ActiveFilterID { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBuildingSceneLayer.</p>


```csharp
public CIMBuildingSceneLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the workspace.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the 3D object rendering filters.</p>


```csharp
public CIMObject3DRenderingFilter[] Filters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMBuildingSceneLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMBuildingSceneLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the sublayers.</p>


```csharp
public string[] SubLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBuildingSceneLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingSceneLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


