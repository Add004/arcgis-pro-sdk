# CIMSymbolLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Represents a symbol layer. Symbol layers are the components that make up a symbol. A symbol layer is represented by a stroke, fill, marker, or procedural symbol layer.</p>


## Object Signature

```csharp
public abstract class CIMSymbolLayer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Represents a symbol layer. Symbol layers are the components that make up a symbol. A symbol layer is represented by a stroke, fill, marker, or procedural symbol layer.</p>


```csharp
protected CIMSymbolLayer()
```
### Animations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the animations that are applied to the symbol layer.</p>


```csharp
public CIMSymbolAnimation[] Animations { get; set; }
```
### ColorLocked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the color set at the basic properties level is applied to the symbol layer. If the symbol layer is color locked then changes made to the color in the basic properties will not be applied to the symbol layer.</p>


```csharp
public bool ColorLocked { get; set; }
```
### Effects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets whether the geometric effects that are applied to the symbol layer. Effects dynamically alter the feature geometry when the symbology is applied. Multiple effects applied to a symbol layer are rendered sequentially.</p>


```csharp
public CIMGeometricEffect[] Effects { get; set; }
```
### Enable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the symbol layer is visible. The symbol layer draws only when enabled. Currently, an invisible layer is not considered in any transformations when in a 3D context.</p>


```csharp
public bool Enable { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the internal name of the symbol layer used for symbol level drawing.</p>


```csharp
public string Name { get; set; }
```
### Overprint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the symbol layer should overprint in press printing.</p>


```csharp
public bool Overprint { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


