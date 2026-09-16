# CIMGeometricEffectJog

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Represents the jog geometric effect which creates a dynamic line with a jog of a specified angle, position, and width in the line.</p>


## Object Signature

```csharp
public class CIMGeometricEffectJog : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectJog()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Represents the jog geometric effect which creates a dynamic line with a jog of a specified angle, position, and width in the line.</p>


```csharp
public CIMGeometricEffectJog()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Gets or sets the angle of the jog in the line which is measured in degrees.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectJog.</p>


```csharp
public CIMGeometricEffectJog Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectJog with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectJog FromJson(string json, JsonDeserializationSettings settings = null)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Gets or sets the length of the segment that forms the jog in the line.</p>


```csharp
public double Length { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Gets or sets the location of the center of the jog, as a percentage measured from the start of the input geometry.</p>


```csharp
public double Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectJog and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectJog.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


