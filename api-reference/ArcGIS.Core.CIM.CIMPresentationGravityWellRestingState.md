# CIMPresentationGravityWellRestingState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Presentation map gravity well resting state.</p>


## Object Signature

```csharp
public class CIMPresentationGravityWellRestingState : CIMPresentationMapRestingState, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">When a presentation map page has an active gravity well resting state, the camera will be pulled back to the specified view point within the given time (travel time) if left idle.</p>


## Members

### CIMPresentationGravityWellRestingState()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Presentation map gravity well resting state.</p>


```csharp
public CIMPresentationGravityWellRestingState()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationGravityWellRestingState.</p>


```csharp
public CIMPresentationGravityWellRestingState Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationGravityWellRestingState with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationGravityWellRestingState FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationGravityWellRestingState and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TravelTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Gets or sets the number of seconds that it will take to travel back to the viewpoint.</p>


```csharp
public double TravelTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationGravityWellRestingState.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


