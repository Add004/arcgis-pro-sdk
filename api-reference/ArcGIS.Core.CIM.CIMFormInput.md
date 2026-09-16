# CIMFormInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInput.yml" sourcestartlinenumber="1">Represents a collection method for a field's value. This is the base class for the
various ways input may be collected from users, such as text boxes, combo boxes,
date pickers and so on.</p>


## Object Signature

```csharp
public abstract class CIMFormInput : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInput.yml" sourcestartlinenumber="1">Represents a collection method for a field's value. This is the base class for the
various ways input may be collected from users, such as text boxes, combo boxes,
date pickers and so on.</p>


```csharp
protected CIMFormInput()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


