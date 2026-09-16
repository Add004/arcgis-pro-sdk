# CIMGeometricEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffect.yml" sourcestartlinenumber="1">Represents a geometric effect, this is base class for all geometric effects.</p>


## Object Signature

```csharp
public abstract class CIMGeometricEffect : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffect.yml" sourcestartlinenumber="1">Represents a geometric effect, this is base class for all geometric effects.</p>


```csharp
protected CIMGeometricEffect()
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffect.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


