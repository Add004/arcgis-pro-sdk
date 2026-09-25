# CIMRelateInfoBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Represents relate base.</p>


## Object Signature

```csharp
public abstract class CIMRelateInfoBase : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRelateInfoBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Represents relate base.</p>


```csharp
protected CIMRelateInfoBase()
```
### Cardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the relate cardinality.</p>


```csharp
public esriRelCardinality Cardinality { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the relate data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### ForeignKey

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the foreign key.</p>


```csharp
public string ForeignKey { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### PrimaryKey

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the primary key.</p>


```csharp
public string PrimaryKey { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelatedMapMemberURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets the related layer/table URI.
<remark>
This value is used to disambiguate cases where the same data connection is used by multiple layers or tables in a map.
</remark></p>


```csharp
public string RelatedMapMemberURI { get; set; }
```
### ServiceRelateID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Gets or sets a integer indicating the relate ID when published in a map service.</p>


```csharp
public int ServiceRelateID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfoBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


