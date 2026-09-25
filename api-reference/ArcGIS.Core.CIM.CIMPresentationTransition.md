# CIMPresentationTransition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Represents a transition.</p>


## Object Signature

```csharp
public class CIMPresentationTransition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationTransition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Represents a transition.</p>


```csharp
public CIMPresentationTransition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationTransition.</p>


```csharp
public CIMPresentationTransition Clone()
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Gets or sets the transition duration in seconds.</p>


```csharp
public double Duration { get; set; }
```
### FlyTransitionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Gets or sets the fly transition mode: Hop, Linear, etc.</p>


```csharp
public AnimationTransition FlyTransitionMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationTransition with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationTransition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SwipeDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Gets or sets the swipe transition direction.</p>


```csharp
public SwipeDirection SwipeDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationTransition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransitionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Gets or sets the transition type.</p>


```csharp
public PresentationTransitionType TransitionType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationTransition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


