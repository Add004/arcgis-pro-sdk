# CIMGeometricEffectRadial

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Represents the radial geometric effect which creates a dynamic line of a specified length and angle originating from a point feature.</p>


## Object Signature

```csharp
public class CIMGeometricEffectRadial : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectRadial()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Represents the radial geometric effect which creates a dynamic line of a specified length and angle originating from a point feature.</p>


```csharp
public CIMGeometricEffectRadial()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Gets or sets the orientation of the line from the marker. The angle is calculated in a counterclockwise manner with 0 degrees equal to due east.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectRadial.</p>


```csharp
public CIMGeometricEffectRadial Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectRadial with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectRadial FromJson(string json, JsonDeserializationSettings settings = null)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Gets or sets the distance of the line from end to end.</p>


```csharp
public double Length { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectRadial and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRadial.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


