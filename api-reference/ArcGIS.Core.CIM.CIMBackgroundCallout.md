# CIMBackgroundCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Represents a background callout which draws a callout with an optional polygon background and leader line.</p>


## Object Signature

```csharp
public class CIMBackgroundCallout : CIMLineCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBackgroundCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Represents a background callout which draws a callout with an optional polygon background and leader line.</p>


```csharp
public CIMBackgroundCallout()
```
### AccentBarSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the accent bar. If null, the accent bar doesn't draw.</p>


```csharp
public CIMLineSymbol AccentBarSymbol { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the background. If null, the background doesn't draw.</p>


```csharp
public CIMPolygonSymbol BackgroundSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBackgroundCallout.</p>


```csharp
public CIMBackgroundCallout Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Reconstructs the CIMBackgroundCallout with a specified state from a JSON encoding.</p>


```csharp
public static CIMBackgroundCallout FromJson(string json, JsonDeserializationSettings settings = null)
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Gets or sets the text margin defining the space around the text that is accounted for in background creation.</p>


```csharp
public CIMTextMargin Margin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBackgroundCallout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBackgroundCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


