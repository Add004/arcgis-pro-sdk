# CIMSymbolAnimation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Represents an animation of a symbol, this is the base class for all animations.</p>


## Object Signature

```csharp
public abstract class CIMSymbolAnimation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolAnimation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Represents an animation of a symbol, this is the base class for all animations.</p>


```csharp
protected CIMSymbolAnimation()
```
### AnimatedSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Gets or sets the animated symbol properties.</p>


```csharp
public CIMAnimatedSymbolProperties AnimatedSymbolProperties { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


