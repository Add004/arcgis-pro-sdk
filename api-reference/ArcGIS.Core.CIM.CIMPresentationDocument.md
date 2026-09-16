# CIMPresentationDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Represents a presentation document which is the document type used for saving .prsx files.</p>


## Object Signature

```csharp
public class CIMPresentationDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Represents a presentation document which is the document type used for saving .prsx files.</p>


```csharp
public CIMPresentationDocument()
```
### BinaryReferences

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the binary references in the document.</p>


```csharp
public CIMBinaryReference[] BinaryReferences { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationDocument.</p>


```csharp
public CIMPresentationDocument Clone()
```
### ElevationSurfaceLayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer definitions in the document.</p>


```csharp
public CIMDefinition[] ElevationSurfaceLayerDefinitions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the layer definitions in the document.</p>


```csharp
public CIMDefinition[] LayerDefinitions { get; set; }
```
### LinkChartDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the link chart definitions in the document.</p>


```csharp
public CIMDefinition[] LinkChartDefinitions { get; set; }
```
### MapDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the map definitions in the document.</p>


```csharp
public CIMDefinition[] MapDefinitions { get; set; }
```
### PresentationDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the presentation definition in the document.</p>


```csharp
public CIMPresentation PresentationDefinition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TableDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the table definitions in the document.</p>


```csharp
public CIMDefinition[] TableDefinitions { get; set; }
```
### TimelineDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the timeline definitions in the document.</p>


```csharp
public CIMDefinition[] TimelineDefinitions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VideoDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Gets or sets the video definitions in the document.</p>


```csharp
public CIMDefinition[] VideoDefinitions { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


