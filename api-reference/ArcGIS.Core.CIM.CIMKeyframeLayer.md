# CIMKeyframeLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Represents a layer keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeLayer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">The layer keyframe stores the path to the layer, the visibility state and defines the transitions for the visibility of the layer.</p>


## Members

### CIMKeyframeLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Represents a layer keyframe.</p>


```csharp
public CIMKeyframeLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeLayer.</p>


```csharp
public CIMKeyframeLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the layer.</p>


```csharp
public string LayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SwipeDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the direction to clip from an edge.</p>


```csharp
public SwipeDirection SwipeDirection { get; set; }
```
### SwipePercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the amount of the visible area to clip.</p>


```csharp
public double SwipePercent { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Transparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the transparency of the keyframe as a percentage.</p>


```csharp
public double Transparency { get; set; }
```
### TransparencyTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the transparency of the layer.</p>


```csharp
public AnimationTransition TransparencyTransition { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration.</p>


```csharp
public double VerticalExaggeration { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeLayer.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration.</p>


```csharp
public double ZOffset { get; set; }
```


