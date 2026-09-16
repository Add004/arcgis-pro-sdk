# CIMPresentationMapRestingState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Presentation map resting state.</p>


## Object Signature

```csharp
public abstract class CIMPresentationMapRestingState : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationMapRestingState()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Presentation map resting state.</p>


```csharp
protected CIMPresentationMapRestingState()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this resting state is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartDelay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Gets or sets the number of seconds to delay before starting.</p>


```csharp
public double StartDelay { get; set; }
```
### Viewpoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Gets or sets the camera.</p>


```csharp
public CIMViewCamera Viewpoint { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapRestingState.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


