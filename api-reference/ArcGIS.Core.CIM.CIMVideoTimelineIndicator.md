# CIMVideoTimelineIndicator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineIndicator.yml" sourcestartlinenumber="1">Represents an indicator on a video timeline.</p>


## Object Signature

```csharp
public abstract class CIMVideoTimelineIndicator : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoTimelineIndicator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineIndicator.yml" sourcestartlinenumber="1">Represents an indicator on a video timeline.</p>


```csharp
protected CIMVideoTimelineIndicator()
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineIndicator.yml" sourcestartlinenumber="1">Gets or sets the indicator label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineIndicator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoTimelineIndicator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


