# CIMBuildingDisciplineSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Represents a building discipline scene layer.</p>


## Object Signature

```csharp
public class CIMBuildingDisciplineSceneLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBuildingDisciplineSceneLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Represents a building discipline scene layer.</p>


```csharp
public CIMBuildingDisciplineSceneLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBuildingDisciplineSceneLayer.</p>


```csharp
public CIMBuildingDisciplineSceneLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMBuildingDisciplineSceneLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMBuildingDisciplineSceneLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Gets or sets identifier that will be used to identify the layer in a building.</p>


```csharp
public int SubLayerID { get; set; }
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the sublayers.</p>


```csharp
public string[] SubLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBuildingDisciplineSceneLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingDisciplineSceneLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


