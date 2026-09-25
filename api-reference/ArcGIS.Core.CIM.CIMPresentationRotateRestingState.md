# CIMPresentationRotateRestingState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Presentation map rotate resting state.</p>


## Object Signature

```csharp
public class CIMPresentationRotateRestingState : CIMPresentationMapRestingState, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">When a presentation map page has an active rotate resting state, the camera will be rotated around the specified view point at the given rotational velocity.</p>


## Members

### CIMPresentationRotateRestingState()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Presentation map rotate resting state.</p>


```csharp
public CIMPresentationRotateRestingState()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationRotateRestingState.</p>


```csharp
public CIMPresentationRotateRestingState Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationRotateRestingState with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationRotateRestingState FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Gets or sets the rotational velocity in degrees per second. A negative value indicates counterclockwise rotation.</p>


```csharp
public double RotationRate { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationRotateRestingState and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationRotateRestingState.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


