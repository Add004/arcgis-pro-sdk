# CIMVisualEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualEffect.yml" sourcestartlinenumber="1">Represents a visual effect definition for stylized rendering of all the content in a map or scene.</p>


## Object Signature

```csharp
public abstract class CIMVisualEffect : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVisualEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualEffect.yml" sourcestartlinenumber="1">Represents a visual effect definition for stylized rendering of all the content in a map or scene.</p>


```csharp
protected CIMVisualEffect()
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the effect should be applied to the scene.</p>


```csharp
public bool IsActive { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


