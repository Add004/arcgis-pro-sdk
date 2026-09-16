# CIMDepthOfFieldEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Represents the data for simulating camera depth of field effect in 3D scenes.</p>


## Object Signature

```csharp
public class CIMDepthOfFieldEffect : CIMCameraEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDepthOfFieldEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Represents the data for simulating camera depth of field effect in 3D scenes.</p>


```csharp
public CIMDepthOfFieldEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDepthOfFieldEffect.</p>


```csharp
public CIMDepthOfFieldEffect Clone()
```
### FocusDepth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Gets or sets the camera's focus depth measured in meters.</p>


```csharp
public double FocusDepth { get; set; }
```
### FocusDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Gets or sets the camera's focus distance measured in meters.</p>


```csharp
public double FocusDistance { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMDepthOfFieldEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMDepthOfFieldEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxBlur

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Gets or sets the kernel size indicating the maximum blur radius.</p>


```csharp
public DepthOfFieldMaxBlur MaxBlur { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDepthOfFieldEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDepthOfFieldEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


