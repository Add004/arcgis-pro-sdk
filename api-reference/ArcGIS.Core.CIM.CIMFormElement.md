# CIMFormElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormElement.yml" sourcestartlinenumber="1">Represents an atomic part of a form. This is the base class for the
various form elements, including inputs connected to fields, grouping
of elements into logical sections of the form, adding attachments,
and so on.</p>


## Object Signature

```csharp
public abstract class CIMFormElement : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormElement.yml" sourcestartlinenumber="1">Represents an atomic part of a form. This is the base class for the
various form elements, including inputs connected to fields, grouping
of elements into logical sections of the form, adding attachments,
and so on.</p>


```csharp
protected CIMFormElement()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


