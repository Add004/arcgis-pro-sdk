# CIMCompositeCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Represents a composite callout. Composite callouts are a filled background along with an optional shadow, which is placed
behind text. They may also have a leader line (consisting of one or both of a simple line, and filled dart)
connecting the callout to an anchor point. Composite callouts may have additional surrounding text elements.
The text representing these parts is specified in the text string using tags. Their relative position properties are
specified in the CIMCompositeCallout through their corresponding CIMCompositeTextPartPosition elements specified below,
but these properties can also be overridden with tag attributes.</p>


## Object Signature

```csharp
public class CIMCompositeCallout : CIMCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCompositeCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Represents a composite callout. Composite callouts are a filled background along with an optional shadow, which is placed
behind text. They may also have a leader line (consisting of one or both of a simple line, and filled dart)
connecting the callout to an anchor point. Composite callouts may have additional surrounding text elements.
The text representing these parts is specified in the text string using tags. Their relative position properties are
specified in the CIMCompositeCallout through their corresponding CIMCompositeTextPartPosition elements specified below,
but these properties can also be overridden with tag attributes.</p>


```csharp
public CIMCompositeCallout()
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the background.</p>


```csharp
public CIMPolygonSymbol BackgroundSymbol { get; set; }
```
### Bottom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the bottom part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition Bottom { get; set; }
```
### BottomLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the bottom left part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition BottomLeft { get; set; }
```
### BottomRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the bottom right part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition BottomRight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCompositeCallout.</p>


```csharp
public CIMCompositeCallout Clone()
```
### CornerRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the callout corner radius in points.
0.0 corresponds to a rectangle corner.</p>


```csharp
public double CornerRadius { get; set; }
```
### DartSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets a symbol used to draw the dart. This is only used if LeaderLinePercentage is less than 100%.</p>


```csharp
public CIMPolygonSymbol DartSymbol { get; set; }
```
### DartWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the dart width.</p>


```csharp
public double DartWidth { get; set; }
```
### Floating

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the floating part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not. The floating part is anchored below
the bottom text part. If there is no bottom text part it is anchored below the middle text part
plus margins.</p>


```csharp
public CIMCompositeTextPartPosition Floating { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Reconstructs the CIMCompositeCallout with a specified state from a JSON encoding.</p>


```csharp
public static CIMCompositeCallout FromJson(string json, JsonDeserializationSettings settings = null)
```
### LeaderLinePercentage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the percentage of the leader line which is drawn as a line as opposed to a solid dart.</p>


```csharp
public double LeaderLinePercentage { get; set; }
```
### LeaderLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the leader line symbol. This is only used if LeaderLinePercentage is greater than 0%.</p>


```csharp
public CIMLineSymbol LeaderLineSymbol { get; set; }
```
### Left

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the left part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition Left { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text margin defining the space around the text that is accounted for in balloon creation.</p>


```csharp
public CIMTextMargin Margin { get; set; }
```
### Middle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the middle part of the callout text.
This contains the relative positioning information. Split offset and box will have no
effect on this text part, since it is required that the middle part is in the center
of the callout.</p>


```csharp
public CIMCompositeTextPartPosition Middle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Right

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the right part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition Right { get; set; }
```
### ShadowSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the shadow symbol for the callout.</p>


```csharp
public CIMPolygonSymbol ShadowSymbol { get; set; }
```
### ShadowXOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the shadow offset from the callout symbol in the horizontal direction. If X and Y are zero, no shadow is drawn.</p>


```csharp
public double ShadowXOffset { get; set; }
```
### ShadowYOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the shadow offset from the callout symbol in the vertical direction. If X and Y are zero, no shadow is drawn.</p>


```csharp
public double ShadowYOffset { get; set; }
```
### SnapLeaderToCornersOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the leader line should snap only to corners.</p>


```csharp
public bool SnapLeaderToCornersOnly { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCompositeCallout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Top

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the top part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition Top { get; set; }
```
### TopLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the top left part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition TopLeft { get; set; }
```
### TopRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Gets or sets the text part position properties for the top right part of the callout text.
This contains the relative positioning information, as well as split offset indicating
the extent to which the callout part will mask the callout outline, and whether or not the
part should be boxed in by the overall callout, or not.</p>


```csharp
public CIMCompositeTextPartPosition TopRight { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


