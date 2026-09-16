# CIMLayerDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Represents a layer document which is the document type used for saving .lyrx files.</p>


## Object Signature

```csharp
public class CIMLayerDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Represents a layer document which is the document type used for saving .lyrx files.</p>


```csharp
public CIMLayerDocument()
```
### BinaryReferences

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the binary references of the document.</p>


```csharp
public CIMBinaryReference[] BinaryReferences { get; set; }
```
### CMYKColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the name of the CMYK color profile of this layer's source map.</p>


```csharp
public string CMYKColorProfile { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerDocument.</p>


```csharp
public CIMLayerDocument Clone()
```
### ElevationSurfaceLayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer definitions.</p>


```csharp
public CIMDefinition[] ElevationSurfaceLayerDefinitions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the layer definitions in the layer document.</p>


```csharp
public CIMDefinition[] LayerDefinitions { get; set; }
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the URIs of the top-level layers stored in this layer document.</p>


```csharp
public string[] Layers { get; set; }
```
### RGBColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the name of the RGB color profile of this layer's source map.</p>


```csharp
public string RGBColorProfile { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TableDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the table definitions in the layer document.</p>


```csharp
public CIMDefinition[] TableDefinitions { get; set; }
```
### Tables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Gets or sets the URIs of the top-level tables stored in this layer document.</p>


```csharp
public string[] Tables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


