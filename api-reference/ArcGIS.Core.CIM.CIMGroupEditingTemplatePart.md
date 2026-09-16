# CIMGroupEditingTemplatePart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Represents a group editing template part.</p>


## Object Signature

```csharp
public class CIMGroupEditingTemplatePart : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroupEditingTemplatePart()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Represents a group editing template part.</p>


```csharp
public CIMGroupEditingTemplatePart()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroupEditingTemplatePart.</p>


```csharp
public CIMGroupEditingTemplatePart Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Reconstructs the CIMGroupEditingTemplatePart with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroupEditingTemplatePart FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer this template is defined for.</p>


```csharp
public string LayerURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### Options

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Gets or sets the options.</p>


```csharp
public IDictionary<string, object> Options { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroupEditingTemplatePart and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransformationID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Gets or sets the transformation ID.</p>


```csharp
public string TransformationID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupEditingTemplatePart.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


