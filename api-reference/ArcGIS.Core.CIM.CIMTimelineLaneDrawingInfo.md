# CIMTimelineLaneDrawingInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Represents the timeline lane drawing information.</p>


## Object Signature

```csharp
public class CIMTimelineLaneDrawingInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimelineLaneDrawingInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Represents the timeline lane drawing information.</p>


```csharp
public CIMTimelineLaneDrawingInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimelineLaneDrawingInfo.</p>


```csharp
public CIMTimelineLaneDrawingInfo Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the color ramp for the time span symbols.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMTimelineLaneDrawingInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimelineLaneDrawingInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxNumberOfCascadeRows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the max number of cascade rows for this timeline lane.</p>


```csharp
public int MaxNumberOfCascadeRows { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolStyleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the timeline symbol style type.</p>


```csharp
public TimelineSymbolStyleType SymbolStyleType { get; set; }
```
### TimeSpanSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the timeline time spans.</p>


```csharp
public CIMLineSymbol TimeSpanSymbol { get; set; }
```
### TimeSpanSymbolBoundary

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the time span symbol boundary preference.</p>


```csharp
public TimeSpanSymbolBoundary TimeSpanSymbolBoundary { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimelineLaneDrawingInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Gets or sets the timeline lane view type.</p>


```csharp
public TimelineLaneViewType ViewType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineLaneDrawingInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


