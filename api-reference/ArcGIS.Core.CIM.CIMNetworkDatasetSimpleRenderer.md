# CIMNetworkDatasetSimpleRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Represents a network dataset simple renderer.</p>


## Object Signature

```csharp
public class CIMNetworkDatasetSimpleRenderer : CIMNetworkDatasetRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkDatasetSimpleRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Represents a network dataset simple renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkDatasetSimpleRenderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the renderer description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkDatasetSimpleRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkDatasetSimpleRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkDatasetSimpleRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetSimpleRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


