# CIMKGType

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type which is used as a base class for entity and relationship types.</p>


## Object Signature

```csharp
public abstract class CIMKGType : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGType()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Type which is used as a base class for entity and relationship types.</p>


```csharp
protected CIMKGType()
```
### ColorInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Gets or sets the color information for the type.</p>


```csharp
public CIMKGColorInfo ColorInfo { get; set; }
```
### GeometryType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Gets or sets the geometry type of the type.</p>


```csharp
public esriGeometryType GeometryType { get; set; }
```
### Indexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Gets or sets the indexes of the type.</p>


```csharp
public CIMKGTypeIndex[] Indexes { get; set; }
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Gets or sets the properties of the type.</p>


```csharp
public CIMKGTypeProperty[] Properties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TypeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Gets or sets the name of the type.</p>


```csharp
public string TypeName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGType.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


