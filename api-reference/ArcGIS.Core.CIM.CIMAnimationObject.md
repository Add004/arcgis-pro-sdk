# CIMAnimationObject

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Provides access to properties of an animation object.</p>


## Object Signature

```csharp
public abstract class CIMAnimationObject : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationObject()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Provides access to properties of an animation object.</p>


```csharp
protected CIMAnimationObject()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Gets or sets an identifier for the user.</p>


```csharp
public string Alias { get; set; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Gets or sets a unique identifier to be accessed by keyframes in the animation.</p>


```csharp
public int ID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationObject.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


