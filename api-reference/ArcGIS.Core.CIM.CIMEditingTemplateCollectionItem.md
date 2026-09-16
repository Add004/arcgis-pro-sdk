# CIMEditingTemplateCollectionItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollectionItem.yml" sourcestartlinenumber="1">Represents an item that can be stored within an editing template collection.</p>


## Object Signature

```csharp
public abstract class CIMEditingTemplateCollectionItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMEditingTemplateCollectionItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollectionItem.yml" sourcestartlinenumber="1">Represents an item that can be stored within an editing template collection.</p>


```csharp
protected CIMEditingTemplateCollectionItem()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollectionItem.yml" sourcestartlinenumber="1">Gets or sets the name of this item.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollectionItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMEditingTemplateCollectionItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


