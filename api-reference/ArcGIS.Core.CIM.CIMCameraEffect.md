# CIMCameraEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCameraEffect.yml" sourcestartlinenumber="1">Represents a camera effect definition to be applied to a 3D view.</p>


## Object Signature

```csharp
public abstract class CIMCameraEffect : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCameraEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCameraEffect.yml" sourcestartlinenumber="1">Represents a camera effect definition to be applied to a 3D view.</p>


```csharp
protected CIMCameraEffect()
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCameraEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the effect should be applied to the scene.</p>


```csharp
public bool IsActive { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCameraEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCameraEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


