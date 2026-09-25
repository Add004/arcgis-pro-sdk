# CIMAnimationLineKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Properties defining a portion of a line to draw at a single point in time for the animation.</p>


## Object Signature

```csharp
public class CIMAnimationLineKeyframe : CIMAnimationGeometryKeyframe, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationLineKeyframe()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Properties defining a portion of a line to draw at a single point in time for the animation.</p>


```csharp
public CIMAnimationLineKeyframe()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationLineKeyframe.</p>


```csharp
public CIMAnimationLineKeyframe Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationLineKeyframe with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationLineKeyframe FromJson(string json, JsonDeserializationSettings settings = null)
```
### FromRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Gets or sets the ratio of a line to start drawing from.</p>


```csharp
public double FromRatio { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationLineKeyframe and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Gets or sets the ratio of a line to finish drawing to.</p>


```csharp
public double ToRatio { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationLineKeyframe.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


