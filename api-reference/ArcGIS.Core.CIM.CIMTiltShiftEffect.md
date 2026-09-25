# CIMTiltShiftEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Represents the data for simulating camera tilt-shift effect for creating a miniaturization effect in 3D scenes.</p>


## Object Signature

```csharp
public class CIMTiltShiftEffect : CIMCameraEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTiltShiftEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Represents the data for simulating camera tilt-shift effect for creating a miniaturization effect in 3D scenes.</p>


```csharp
public CIMTiltShiftEffect()
```
### BlurStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Gets or sets the strength (0-1) of the tilt-shift blur.</p>


```csharp
public double BlurStrength { get; set; }
```
### BottomOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Gets or sets the width of the blurred area starting from the bottom of the screen measured in points.</p>


```csharp
public double BottomOffset { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTiltShiftEffect.</p>


```csharp
public CIMTiltShiftEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMTiltShiftEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMTiltShiftEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### LeftOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Gets or sets the width of the blurred area starting from the left of the screen measured in points.</p>


```csharp
public double LeftOffset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RightOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Gets or sets the width of the blurred area starting from the right of the screen measured in points.</p>


```csharp
public double RightOffset { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTiltShiftEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TopOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Gets or sets the width of the blurred area starting from the top of the screen measured in points.</p>


```csharp
public double TopOffset { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTiltShiftEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


