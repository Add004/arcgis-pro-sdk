# CIMCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Represents a callout.</p>


## Object Signature

```csharp
public abstract class CIMCallout : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Callouts are used to define additional ornamentation for a symbol. The primary use for callouts is to add leader line capabilities to text. Callouts are also used for defining items such as highway shields, balloon callouts, and more complex text box and leader line combinations. All callouts have some capability to draw leader lines; therefore they share a base property of a leader tolerance.</p>


## Members

### CIMCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Represents a callout.</p>


```csharp
protected CIMCallout()
```
### LeaderOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Gets or sets the leader offset which is an offset value defining the distance (in points) between the anchor point and the beginning of the drawn leader.</p>


```csharp
public double LeaderOffset { get; set; }
```
### LeaderTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Gets or sets the leader tolerance which is the closest distance (in points) to the text the anchor point can be for the callout to draw.</p>


```csharp
public double LeaderTolerance { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


