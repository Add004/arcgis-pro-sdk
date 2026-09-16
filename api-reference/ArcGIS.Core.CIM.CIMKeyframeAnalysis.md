# CIMKeyframeAnalysis

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Represents an exploratory analysis keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeAnalysis : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKeyframeAnalysis()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Represents an exploratory analysis keyframe.</p>


```csharp
public CIMKeyframeAnalysis()
```
### Analysis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Gets or sets the exploratory analysis definition.</p>


```csharp
public CIMExploratoryAnalysisDefinition Analysis { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeAnalysis.</p>


```csharp
public CIMKeyframeAnalysis Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeAnalysis with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeAnalysis FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeAnalysis and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Transition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the exploratory analysis item.</p>


```csharp
public AnimationTransition Transition { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeAnalysis.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


