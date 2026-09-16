# CIMVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariable.yml" sourcestartlinenumber="1">Represents a visual variable.</p>


## Object Signature

```csharp
public abstract class CIMVisualVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariable.yml" sourcestartlinenumber="1">Represents a visual variable.</p>


```csharp
protected CIMVisualVariable()
```
### AuthoringInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the authoring info.</p>


```csharp
public CIMVisualVariableAuthoringInfo AuthoringInfo { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


