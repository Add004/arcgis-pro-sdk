# CIMGAIsoRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Represents GA iso renderer.</p>


## Object Signature

```csharp
public class CIMGAIsoRenderer : CIMClassBreaksRendererBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGAIsoRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Represents GA iso renderer.</p>


```csharp
public CIMGAIsoRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGAIsoRenderer.</p>


```csharp
public CIMGAIsoRenderer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMGAIsoRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGAIsoRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsoQuality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Gets or sets the iso quality.</p>


```csharp
public int IsoQuality { get; set; }
```
### IsoType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Gets or sets the iso type.</p>


```csharp
public string IsoType { get; set; }
```
### NoResultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Gets or sets the no result symbol.</p>


```csharp
public CIMSymbolReference NoResultSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RefineOnZoom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to refine on zoom.</p>


```csharp
public bool RefineOnZoom { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGAIsoRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGAIsoRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


