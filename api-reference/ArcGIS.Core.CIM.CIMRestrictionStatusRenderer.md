# CIMRestrictionStatusRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Represents a renderer that shows the restriction status of network elements.</p>


## Object Signature

```csharp
public class CIMRestrictionStatusRenderer : CIMNetworkDatasetRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRestrictionStatusRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Represents a renderer that shows the restriction status of network elements.</p>


```csharp
public CIMRestrictionStatusRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRestrictionStatusRenderer.</p>


```csharp
public CIMRestrictionStatusRenderer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMRestrictionStatusRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRestrictionStatusRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RendererTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Gets or sets the renderer target.</p>


```csharp
public NDSRendererTarget RendererTarget { get; set; }
```
### RestrictionStatusSymbolClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Gets or sets the restriction status symbol classes.
if advanced mode (is classify by preference level): all but GeneralTraversable can be applicable.
if basic mode (is NOT classify by preference level): only Prohibited, GeneralTraversable, and Invalid can be applicable.
MixedPreferenceLevelTraversable only applicable to NDSRendererTarget.Edges.</p>


```csharp
public CIMRestrictionStatusSymbolClass[] RestrictionStatusSymbolClasses { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRestrictionStatusRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TraversableDirectionsAdornerPointSymbolClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Gets or sets the traversable directions adorner point symbol classes.
Only applicable to NDSRendererTarget.Edges.
Independent of classify by preference level setting.</p>


```csharp
public CIMTraversableDirectionsAdornerPointSymbolClass[] TraversableDirectionsAdornerPointSymbolClasses { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


