# CIMSymbolAnimationMoveAlongLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Represents the move along line animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationMoveAlongLine : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Dynamically animates marker(s) along a line. The animation can be defined by either distance along the line or speed.
The initial marker placement for the animation is determined by the MarkerPlacement property on the symbol layer, and the animation will move the marker(s) from that initial placement along the line.</p>


## Members

### CIMSymbolAnimationMoveAlongLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Represents the move along line animation.</p>


```csharp
public CIMSymbolAnimationMoveAlongLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationMoveAlongLine.</p>


```csharp
public CIMSymbolAnimationMoveAlongLine Clone()
```
### Continuous

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the animation will loop continuously when Speed is defined.
If true, once the marker reaches the end of the line it will jump back to the starting placement and repeat the animation continuously until the duration is reached.</p>


```csharp
public bool Continuous { get; set; }
```
### DistanceAlong

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Gets or sets the distance as a percentage along the line to which the marker will animate.
0 corresponds to the starting placement of the marker, and 100 corresponds to a full movement along the line.
This is only used if MovementType is set to Distance.</p>


```csharp
public double DistanceAlong { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationMoveAlongLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationMoveAlongLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### MovementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Gets or sets the movement type, indicating whether the marker animates along the line by distance or by speed.</p>


```csharp
public MovementAlongLineType MovementType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Speed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Gets or sets the speed at which the marker will animate along the line, in units of the line's unit per second.
When the MovementType is set to Distance, the marker will move along the line at this speed until it reaches the DistanceAlong value.
When the MovementType is set to Speed, the marker will move along the line at this speed, and DistanceAlong is ignored.</p>


```csharp
public double Speed { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationMoveAlongLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationMoveAlongLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


