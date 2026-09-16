# CIMView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Represents a view in the project.</p>


## Object Signature

```csharp
public abstract class CIMView : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Represents a view in the project.</p>


```csharp
protected CIMView()
```
### InstanceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Gets or sets the instance identifier of this view.</p>


```csharp
public int InstanceID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ViewType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Gets or sets the view type as a string.</p>


```csharp
public string ViewType { get; set; }
```
### ViewableObjectPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Gets or sets the path of the item in the view.</p>


```csharp
public string ViewableObjectPath { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


