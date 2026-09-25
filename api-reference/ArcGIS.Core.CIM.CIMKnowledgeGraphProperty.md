# CIMKnowledgeGraphProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Property used for entities and relationships.</p>


## Object Signature

```csharp
public abstract class CIMKnowledgeGraphProperty : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphProperty()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Loading Property used for entities and relationships.</p>


```csharp
protected CIMKnowledgeGraphProperty()
```
### Merge

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this property should be used
to determine a merge.</p>


```csharp
public bool Merge { get; set; }
```
### MissingDataValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets or sets the value to use when import data is missing.  This
value is used when the Value property results in a null or empty value.</p>


```csharp
public CIMKnowledgeGraphFixedPropertyValue MissingDataValue { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets or sets the name of the property.</p>


```csharp
public string Name { get; set; }
```
### PropertyType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets or sets the type of the property.</p>


```csharp
public esriFieldType PropertyType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Gets or sets the value which is to be imported.
Value will have to be tested for type in order to properly perform the import.</p>


```csharp
public CIMKnowledgeGraphPropertyValue Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphProperty.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


