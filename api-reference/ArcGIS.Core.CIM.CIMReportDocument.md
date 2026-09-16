# CIMReportDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Represents a report document which is the document type used for saving .rlfx files.</p>


## Object Signature

```csharp
public class CIMReportDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReportDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Represents a report document which is the document type used for saving .rlfx files.</p>


```csharp
public CIMReportDocument()
```
### BinaryReferences

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the binary references of the document.</p>


```csharp
public CIMBinaryReference[] BinaryReferences { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReportDocument.</p>


```csharp
public CIMReportDocument Clone()
```
### ElevationSurfaceLayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer definitions.</p>


```csharp
public CIMDefinition[] ElevationSurfaceLayerDefinitions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMReportDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMReportDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the layer definitions in the report document.</p>


```csharp
public CIMDefinition[] LayerDefinitions { get; set; }
```
### LayoutDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the layout definitions referenced by supplemental pages of the report document.</p>


```csharp
public CIMDefinition[] LayoutDefinitions { get; set; }
```
### LinkChartDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the link chart definitions of the report document.</p>


```csharp
public CIMDefinition[] LinkChartDefinitions { get; set; }
```
### MapDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the map definitions of the report document.</p>


```csharp
public CIMDefinition[] MapDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReportDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the report definition of the report document.</p>


```csharp
public CIMReport ReportDefinition { get; set; }
```
### TableDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the table definitions of the report document.</p>


```csharp
public CIMDefinition[] TableDefinitions { get; set; }
```
### TimelineDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the timeline definitions of the report document.</p>


```csharp
public CIMDefinition[] TimelineDefinitions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReportDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VideoDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Gets or sets the video definitions of the report document.</p>


```csharp
public CIMDefinition[] VideoDefinitions { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReportDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


