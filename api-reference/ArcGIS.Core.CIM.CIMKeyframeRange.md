# CIMKeyframeRange

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Represents a range keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeRange : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">The range keyframe stores the map range and defines the transitions for the minimum and maximum value in the range.</p>


## Members

### CIMKeyframeRange()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Represents a range keyframe.</p>


```csharp
public CIMKeyframeRange()
```
### ActiveRangeLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer with the active range. Specify a single layer or leave empty to indicate all layers that share the active range name.</p>


```csharp
public string ActiveRangeLayer { get; set; }
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the active range name. Used to update which range is active.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeRange.</p>


```csharp
public CIMKeyframeRange Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeRange with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeRange FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsExclusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the range should be all values less than the minimum value and greater than the maximum value.</p>


```csharp
public bool IsExclusion { get; set; }
```
### LayerRangeExtents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the layer range extents. Each layer range applies to a single map.</p>


```csharp
public CIMLayerRange[] LayerRangeExtents { get; set; }
```
### LayerRangeTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the layer range extents.</p>


```csharp
public AnimationTransition LayerRangeTransition { get; set; }
```
### MaxTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the maximum value of the range.</p>


```csharp
public AnimationTransition MaxTransition { get; set; }
```
### MinTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the minimum value of the range.</p>


```csharp
public AnimationTransition MinTransition { get; set; }
```
### Range

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the value of the active range.</p>


```csharp
public CIMRange Range { get; set; }
```
### RangeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Gets or sets the range relation.</p>


```csharp
public RangeRelation RangeRelation { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeRange and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeRange.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


