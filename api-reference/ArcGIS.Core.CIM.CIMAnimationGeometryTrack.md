# CIMAnimationGeometryTrack

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Properties defining a geometry track for animating a geometry.</p>


## Object Signature

```csharp
public class CIMAnimationGeometryTrack : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationGeometryTrack()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Properties defining a geometry track for animating a geometry.</p>


```csharp
public CIMAnimationGeometryTrack()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Gets or sets an identifier for the user.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationGeometryTrack.</p>


```csharp
public CIMAnimationGeometryTrack Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationGeometryTrack with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationGeometryTrack FromJson(string json, JsonDeserializationSettings settings = null)
```
### Keyframes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Gets or sets the collection of animation geometry keyframes.</p>


```csharp
public CIMAnimationGeometryKeyframe[] Keyframes { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Gets or sets the ID of the CIMAnimationSymbol to be used by this track.</p>


```csharp
public int SymbolID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationGeometryTrack and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryTrack.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


