# CIMFrameElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Represents the frame that is associated with some element types (for example, map frame, legends and so on).</p>


## Object Signature

```csharp
public abstract class CIMFrameElement : CIMElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFrameElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Represents the frame that is associated with some element types (for example, map frame, legends and so on).</p>


```csharp
protected CIMFrameElement()
```
### Frame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Gets or sets the geometry of a frame for an element.</p>


```csharp
public Polygon Frame { get; set; }
```
### GraphicFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Gets or sets the graphic symbology of an element's frame.</p>


```csharp
public CIMGraphicFrame GraphicFrame { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFrameElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


