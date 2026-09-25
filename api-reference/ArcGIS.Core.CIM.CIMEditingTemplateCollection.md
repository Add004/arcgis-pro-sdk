# CIMEditingTemplateCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Represents a collection of editing templates.</p>


## Object Signature

```csharp
public class CIMEditingTemplateCollection : CIMEditingTemplateCollectionItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingTemplateCollection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Represents a collection of editing templates.</p>


```csharp
public CIMEditingTemplateCollection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMEditingTemplateCollection.</p>


```csharp
public CIMEditingTemplateCollection Clone()
```
### Contents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Gets or sets the array of items stored within this collection.</p>


```csharp
public CIMEditingTemplateCollectionItem[] Contents { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this collection is expanded in the user interface.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Reconstructs the CIMEditingTemplateCollection with a specified state from a JSON encoding.</p>


```csharp
public static CIMEditingTemplateCollection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMEditingTemplateCollection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


