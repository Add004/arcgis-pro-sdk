# CIMTextGraphicBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Represents a text graphic base class, the generic base class for text based graphics.</p>


## Object Signature

```csharp
public abstract class CIMTextGraphicBase : CIMGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTextGraphicBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Represents a text graphic base class, the generic base class for text based graphics.</p>


```csharp
protected CIMTextGraphicBase()
```
### Leaders

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Gets or sets a collection of leaders coming off of the graphic.</p>


```csharp
public CIMLeader[] Leaders { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Gets or sets the geometry of the text graphic.</p>


```csharp
public Geometry Shape { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Gets or sets the text string of the text graphic.</p>


```csharp
public string Text { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTextGraphicBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


