# CIMMapDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Represents a map document which is the document type used for saving .mapx files.</p>


## Object Signature

```csharp
public class CIMMapDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Represents a map document which is the document type used for saving .mapx files.</p>


```csharp
public CIMMapDocument()
```
### BinaryReferences

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the binary references of the document.</p>


```csharp
public CIMBinaryReference[] BinaryReferences { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapDocument.</p>


```csharp
public CIMMapDocument Clone()
```
### ElevationSurfaceLayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer definitions of the map document.</p>


```csharp
public CIMDefinition[] ElevationSurfaceLayerDefinitions { get; set; }
```
### ElevationUnitOverride

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the elevation unit override of the map document.</p>


```csharp
public CIMDisplayUnit ElevationUnitOverride { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMMapDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the layer definitions of the map document.</p>


```csharp
public CIMDefinition[] LayerDefinitions { get; set; }
```
### LinkChartDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the link chart definitions of the map document.</p>


```csharp
public CIMDefinition[] LinkChartDefinitions { get; set; }
```
### LocationUnitOverride

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the location unit override of the map document.</p>


```csharp
public CIMDisplayUnit LocationUnitOverride { get; set; }
```
### MapDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the map definition of the map document.</p>


```csharp
public CIMMap MapDefinition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TableDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the table definitions of the map document.</p>


```csharp
public CIMDefinition[] TableDefinitions { get; set; }
```
### TimelineDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the timeline definitions of the map document.</p>


```csharp
public CIMDefinition[] TimelineDefinitions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VideoDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Gets or sets the video definitions of the map document.</p>


```csharp
public CIMDefinition[] VideoDefinitions { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


