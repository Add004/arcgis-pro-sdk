# CIMBalloonCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Represents a balloon callout. Balloon callouts are a filled background that is placed behind text. They may or may not have a leader line connecting the callout to an anchor point.</p>


## Object Signature

```csharp
public class CIMBalloonCallout : CIMCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBalloonCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Represents a balloon callout. Balloon callouts are a filled background that is placed behind text. They may or may not have a leader line connecting the callout to an anchor point.</p>


```csharp
public CIMBalloonCallout()
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the background.</p>


```csharp
public CIMPolygonSymbol BackgroundSymbol { get; set; }
```
### BalloonStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets the balloon style.</p>


```csharp
public BalloonCalloutStyle BalloonStyle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBalloonCallout.</p>


```csharp
public CIMBalloonCallout Clone()
```
### DartSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets a symbol used to draw the dart.</p>


```csharp
public CIMPolygonSymbol DartSymbol { get; set; }
```
### FixedDartWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets the dart width.</p>


```csharp
public double FixedDartWidth { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Reconstructs the CIMBalloonCallout with a specified state from a JSON encoding.</p>


```csharp
public static CIMBalloonCallout FromJson(string json, JsonDeserializationSettings settings = null)
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets the text margin defining the space around the text that is accounted for in balloon creation.</p>


```csharp
public CIMTextMargin Margin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBalloonCallout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDartSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the dart symbol is drawn differently to the background symbol.</p>


```csharp
public bool UseDartSymbol { get; set; }
```
### UseFixedDartWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use a fixed size when drawing the dart symbol.</p>


```csharp
public bool UseFixedDartWidth { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBalloonCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


