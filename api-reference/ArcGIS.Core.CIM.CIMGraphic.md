# CIMGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Represents a graphic.</p>


## Object Signature

```csharp
public abstract class CIMGraphic : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Represents a graphic.</p>


```csharp
protected CIMGraphic()
```
### Attributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets a property set of attributes. Typically set by the layer or element during draw.</p>


```csharp
public IDictionary<string, object> Attributes { get; set; }
```
### BlendingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets the blending mode of the graphic. Typically set by the layer or element during draw.</p>


```csharp
public BlendingMode BlendingMode { get; set; }
```
### Masks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets an array of masks for the graphic. Set by the layer or element during draw, but not persisted in the project.</p>


```csharp
[Obsolete("Masks is deprecated at 3.3. This property is obsolete.")]
public Array Masks { get; set; }
```
### Placement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets the placement anchor of the graphic.</p>


```csharp
public Anchor Placement { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets the reference scale of the graphic. Typically set by the layer or element during draw.</p>


```csharp
public double ReferenceScale { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets the symbol for the graphic.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Gets or sets the transparency of the graphic as a percentage. Typically set by the layer or element during draw, but not persisted. Change the transparency of layers in the symbol for persistent changes.</p>


```csharp
public double Transparency { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


