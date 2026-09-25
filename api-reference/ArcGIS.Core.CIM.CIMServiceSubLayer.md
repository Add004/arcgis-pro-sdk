# CIMServiceSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Represents a service sublayer.</p>


## Object Signature

```csharp
public class CIMServiceSubLayer : CIMSubLayerBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMServiceSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Represents a service sublayer.</p>


```csharp
public CIMServiceSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMServiceSubLayer.</p>


```csharp
public CIMServiceSubLayer Clone()
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the definition expression.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### DefinitionExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the Name of definition expression.</p>


```csharp
public string DefinitionExpressionName { get; set; }
```
### DefinitionFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the definition filter choices.</p>


```csharp
public CIMDefinitionFilter[] DefinitionFilterChoices { get; set; }
```
### DrawTimeCumulative

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not draw time cumulatively.</p>


```csharp
public bool DrawTimeCumulative { get; set; }
```
### FloorAwareTableProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets floor-aware properties if the sublayer is used in floor filtering.</p>


```csharp
public CIMFloorAwareTableProperties FloorAwareTableProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMServiceSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMServiceSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the layer definition for dynamic service layer. This is a JSON string in REST API syntax.</p>


```csharp
public string LayerDefinition { get; set; }
```
### PopupInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the pop-up info.</p>


```csharp
public CIMPopupInfo PopupInfo { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the primary symbol renderer.</p>


```csharp
public CIMRenderer Renderer { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to scale symbols.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the layer.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### ShowLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show labels.</p>


```csharp
public bool ShowLabels { get; set; }
```
### ShowPopups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show pop-ups.</p>


```csharp
public bool ShowPopups { get; set; }
```
### SourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the source ID.</p>


```csharp
public string SourceID { get; set; }
```
### TimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the time offset.</p>


```csharp
public double TimeOffset { get; set; }
```
### TimeOffsetUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the time offset units.</p>


```csharp
public esriTimeUnits TimeOffsetUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMServiceSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the transparency of the sublayer as a percentage.</p>


```csharp
public double Transparency { get; set; }
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the backing layer. Used when feature layer capabilities are enabled.</p>


```csharp
public string URI { get; set; }
```
### UseTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use time.</p>


```csharp
public bool UseTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


