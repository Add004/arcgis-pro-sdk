# CIMKeyframeTime

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Represents a time keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeTime : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">The time keyframe stores the time extent and defines the transitions for the start and end value in the time extent.</p>


## Members

### CIMKeyframeTime()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Represents a time keyframe.</p>


```csharp
public CIMKeyframeTime()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeTime.</p>


```csharp
public CIMKeyframeTime Clone()
```
### EndTimeTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the end value of the time extent.</p>


```csharp
public AnimationTransition EndTimeTransition { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeTime with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeTime FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTimeTransition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the start value of the time extent.</p>


```csharp
public AnimationTransition StartTimeTransition { get; set; }
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Gets or sets the value of the time extent.</p>


```csharp
public TimeExtent Time { get; set; }
```
### TimeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Gets or sets the time relation.</p>


```csharp
public esriTimeRelation TimeRelation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeTime and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeTime.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


