# CIMBuildingLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Represents a building composite layer.</p>


## Object Signature

```csharp
public class CIMBuildingLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBuildingLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Represents a building composite layer.</p>


```csharp
public CIMBuildingLayer()
```
### ActiveFilterID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the ID of the filter currently used for rendering.</p>


```csharp
public string ActiveFilterID { get; set; }
```
### BuildingDisciplineLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the building discipline composite layers in the project.</p>


```csharp
public string[] BuildingDisciplineLayers { get; set; }
```
### BuildingID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the building ID to filter by building.</p>


```csharp
public string BuildingID { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBuildingLayer.</p>


```csharp
public CIMBuildingLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the workspace.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### ExteriorLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the exterior shell feature layer in the project.</p>


```csharp
public string ExteriorLayer { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the 3D object rendering filters.</p>


```csharp
public CIMObject3DRenderingFilter[] Filters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMBuildingLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMBuildingLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SummaryStatisticsURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the summary statistics.</p>


```csharp
public string SummaryStatisticsURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBuildingLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBuildingLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


