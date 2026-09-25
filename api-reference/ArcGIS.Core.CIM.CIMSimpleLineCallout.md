# CIMSimpleLineCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Represents a simple line callout for drawing basic leader lines.</p>


## Object Signature

```csharp
public class CIMSimpleLineCallout : CIMCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSimpleLineCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Represents a simple line callout for drawing basic leader lines.</p>


```csharp
public CIMSimpleLineCallout()
```
### AutoSnap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to auto-snap the line leaders to the text.</p>


```csharp
public bool AutoSnap { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSimpleLineCallout.</p>


```csharp
public CIMSimpleLineCallout Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Reconstructs the CIMSimpleLineCallout with a specified state from a JSON encoding.</p>


```csharp
public static CIMSimpleLineCallout FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to draw leader lines.</p>


```csharp
public CIMLineSymbol LineSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSimpleLineCallout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleLineCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


