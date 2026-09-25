# CIMAnimationScreenGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Represents a graphic and list of keyframes indicating properties that can be changed during the animation.</p>


## Object Signature

```csharp
public class CIMAnimationScreenGraphic : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationScreenGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Represents a graphic and list of keyframes indicating properties that can be changed during the animation.</p>


```csharp
public CIMAnimationScreenGraphic()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Gets or sets an identifier for the user.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationScreenGraphic.</p>


```csharp
public CIMAnimationScreenGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationScreenGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationScreenGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Graphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic to be displayed.</p>


```csharp
public CIMGraphic Graphic { get; set; }
```
### Keyframes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic properties keyframes.</p>


```csharp
public CIMAnimationScreenGraphicKeyframe[] Keyframes { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationScreenGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationScreenGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


