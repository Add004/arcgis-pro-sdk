# CIMEditingTemplateReference

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Represents a reference to an editing template.</p>


## Object Signature

```csharp
public class CIMEditingTemplateReference : CIMEditingTemplateCollectionItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingTemplateReference()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Represents a reference to an editing template.</p>


```csharp
public CIMEditingTemplateReference()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Creates a deep copy of CIMEditingTemplateReference.</p>


```csharp
public CIMEditingTemplateReference Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Reconstructs the CIMEditingTemplateReference with a specified state from a JSON encoding.</p>


```csharp
public static CIMEditingTemplateReference FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Gets or sets the layer URI where this template is located.</p>


```csharp
public string LayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TemplateName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Gets or sets the name of the template being referenced.</p>


```csharp
public string TemplateName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMEditingTemplateReference and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateReference.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


