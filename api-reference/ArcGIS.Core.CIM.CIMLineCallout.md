# CIMLineCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Represents a line callout.</p>


## Object Signature

```csharp
public abstract class CIMLineCallout : CIMCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLineCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Represents a line callout.</p>


```csharp
protected CIMLineCallout()
```
### Gap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Gets or sets the gap (in points) between the text symbol and the beginning of the leader line.</p>


```csharp
public double Gap { get; set; }
```
### LeaderLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Gets or sets the line symbol to draw leaders with.</p>


```csharp
public CIMLineSymbol LeaderLineSymbol { get; set; }
```
### LineStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Gets or sets the style of line to generate when a Point leader is drawn defined by an enumeration value. Line leaders will always be drawn with their own geometry.</p>


```csharp
public LeaderLineStyle LineStyle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


