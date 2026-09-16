# CIMPencilSketchEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a pencil sketch style.</p>


## Object Signature

```csharp
public class CIMPencilSketchEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPencilSketchEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a pencil sketch style.</p>


```csharp
public CIMPencilSketchEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPencilSketchEffect.</p>


```csharp
public CIMPencilSketchEffect Clone()
```
### CrosshatchAngleCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Gets or sets the number of crosshatch angles.</p>


```csharp
public int CrosshatchAngleCount { get; set; }
```
### CrosshatchStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Gets or sets the strength of the crosshatching.</p>


```csharp
public double CrosshatchStrength { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMPencilSketchEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMPencilSketchEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### Grayscale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to convert scene colors to grayscale.</p>


```csharp
public bool Grayscale { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPencilSketchEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPencilSketchEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


