# CIMMosaicLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Represents a mosaic layer corresponding to a mosaic dataset.</p>


## Object Signature

```csharp
public class CIMMosaicLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMosaicLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Represents a mosaic layer corresponding to a mosaic dataset.</p>


```csharp
public CIMMosaicLayer()
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the name of the active range.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### ActiveVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets an array of the active variables.</p>


```csharp
public string[] ActiveVariables { get; set; }
```
### BoundaryLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the boundary layer.</p>


```csharp
public string BoundaryLayer { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMosaicLayer.</p>


```csharp
public CIMMosaicLayer Clone()
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the definition expression.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### DefinitionExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the Name of definition expression.</p>


```csharp
public string DefinitionExpressionName { get; set; }
```
### DefinitionFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the definition filter choices.</p>


```csharp
public CIMDefinitionFilter[] DefinitionFilterChoices { get; set; }
```
### FootprintLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the footprint layer.</p>


```csharp
public string FootprintLayer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMMosaicLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMMosaicLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImageLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the image layer.</p>


```csharp
public string ImageLayer { get; set; }
```
### MosaicDatasetConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection of the mosaic dataset.</p>


```csharp
public CIMDataConnection MosaicDatasetConnection { get; set; }
```
### PageDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the page definition which allows for using current map series page to filter features.</p>


```csharp
public CIMPageDefinition PageDefinition { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the range definitions of the mosaic dataset.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SeamlineLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the seamline layer.</p>


```csharp
public string SeamlineLayer { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### TimeFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Gets or sets the time fields.</p>


```csharp
public CIMTimeTableDefinition TimeFields { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMosaicLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


