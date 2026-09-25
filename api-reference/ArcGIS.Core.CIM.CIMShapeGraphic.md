# CIMShapeGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic, the generic base class for geometry based graphics.</p>


## Object Signature

```csharp
public abstract class CIMShapeGraphic : CIMGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMShapeGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic, the generic base class for geometry based graphics.</p>


```csharp
protected CIMShapeGraphic()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### PopupHtmlText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Gets or sets the pop-up HTML text.</p>


```csharp
public string PopupHtmlText { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMShapeGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


