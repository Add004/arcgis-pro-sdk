# CIMMapProductSurround

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">The base class for layout surround elements used in producing map products based on industry specifications.</p>


## Object Signature

```csharp
public abstract class CIMMapProductSurround : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapProductSurround()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">The base class for layout surround elements used in producing map products based on industry specifications.</p>


```csharp
protected CIMMapProductSurround()
```
### AutoUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether properties of the surround should update automatically based on changes in the map.</p>


```csharp
public bool AutoUpdate { get; set; }
```
### DrawToSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the element to specification size or allow user to manually resize element.</p>


```csharp
public bool DrawToSpecification { get; set; }
```
### ProductSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">Gets or sets the map product specification type of the surround.</p>


```csharp
public MapProductSpecType ProductSpecification { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductSurround.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


