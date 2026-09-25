# CIMLegendPatch

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendPatch.yml" sourcestartlinenumber="1">Represents a custom legend patch, the small lines or rectangles used to display legend classes.</p>


## Object Signature

```csharp
public abstract class CIMLegendPatch : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLegendPatch()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendPatch.yml" sourcestartlinenumber="1">Represents a custom legend patch, the small lines or rectangles used to display legend classes.</p>


```csharp
protected CIMLegendPatch()
```
### GeometryURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendPatch.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the geometry of the legend patch.</p>


```csharp
public string GeometryURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendPatch.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLegendPatch.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


