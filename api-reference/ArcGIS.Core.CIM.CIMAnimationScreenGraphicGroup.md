# CIMAnimationScreenGraphicGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Represents an animation screen graphic group container.</p>


## Object Signature

```csharp
public class CIMAnimationScreenGraphicGroup : CIMAnimationScreenGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationScreenGraphicGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Represents an animation screen graphic group container.</p>


```csharp
public CIMAnimationScreenGraphicGroup()
```
### Children

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Gets or sets the children.</p>


```csharp
public CIMAnimationScreenGraphic[] Children { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationScreenGraphicGroup.</p>


```csharp
public CIMAnimationScreenGraphicGroup Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationScreenGraphicGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationScreenGraphicGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationScreenGraphicGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphicGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


