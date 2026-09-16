# CIMIndexedSceneLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Represents a indexed scene layer.</p>


## Object Signature

```csharp
public class CIMIndexedSceneLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIndexedSceneLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Represents a indexed scene layer.</p>


```csharp
public CIMIndexedSceneLayer()
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the active range name.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### AssociatedFeatureLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the URI to the associated feature layer.</p>


```csharp
public string AssociatedFeatureLayerURI { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIndexedSceneLayer.</p>


```csharp
public CIMIndexedSceneLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the definition expression that can subset the features.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### DefinitionExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the Name of definition expression.</p>


```csharp
public string DefinitionExpressionName { get; set; }
```
### DefinitionFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the definition filter choices.</p>


```csharp
public CIMDefinitionFilter[] DefinitionFilterChoices { get; set; }
```
### ExclusionSet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the set of excluded features.</p>


```csharp
public long[] ExclusionSet { get; set; }
```
### FeatureElevationExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the feature elevation expression.</p>


```csharp
public string FeatureElevationExpression { get; set; }
```
### FeatureElevationExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the expression for setting the feature elevation.</p>


```csharp
public CIMExpressionInfo FeatureElevationExpressionInfo { get; set; }
```
### FloorAwareTableProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets floor-aware properties if the scene layer is used in floor filtering.</p>


```csharp
public CIMFloorAwareTableProperties FloorAwareTableProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMIndexedSceneLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMIndexedSceneLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndexedSceneLayerType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the indexed scene layer type. Typically set by the system and should not be modified.</p>


```csharp
public IndexedSceneLayerType IndexedSceneLayerType { get; set; }
```
### LabelClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the collection of label class definitions.</p>


```csharp
public CIMLabelClass[] LabelClasses { get; set; }
```
### LabelVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display labels for this layer's label classes.</p>


```csharp
public bool LabelVisibility { get; set; }
```
### ModificationLayerEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the integrated mesh modification is enabled.</p>


```csharp
public bool ModificationLayerEnabled { get; set; }
```
### ModificationLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the modification layer.</p>


```csharp
public string ModificationLayerURI { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets range definitions.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the primary symbol renderer.</p>


```csharp
public CIMRenderer Renderer { get; set; }
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the layer.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the geometries are snappable.</p>


```csharp
public bool Snappable { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### TimeFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets the time fields.</p>


```csharp
public CIMTimeTableDefinition TimeFields { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIndexedSceneLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UsePredefinedMaxScreenThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use predefined max screen threshold as defined in the integrated mesh layer.</p>


```csharp
public bool UsePredefinedMaxScreenThreshold { get; set; }
```
### UseRealWorldSymbolSizes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use real world symbols sizes (meters) vs. points.</p>


```csharp
public bool UseRealWorldSymbolSizes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIndexedSceneLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


