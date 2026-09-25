# CIMLayerTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Represents a layer template.</p>


## Object Signature

```csharp
public class CIMLayerTemplate : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Represents a layer template.</p>


```csharp
public CIMLayerTemplate()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerTemplate.</p>


```csharp
public CIMLayerTemplate Clone()
```
### DataURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Gets or sets the URI of any additional data associated with this template.</p>


```csharp
public string DataURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerTemplate with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerTemplate FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerTemplateId

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Gets or sets the layer template ID.</p>


```csharp
public string LayerTemplateId { get; set; }
```
### Parameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Gets or sets the layer template parameters.</p>


```csharp
public IDictionary<string, object> Parameters { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerTemplate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


