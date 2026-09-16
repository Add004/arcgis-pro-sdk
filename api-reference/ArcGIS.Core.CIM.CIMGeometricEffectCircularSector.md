# CIMGeometricEffectCircularSector

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Represents the circular sector geometric effect which creates a circular sector of a specified radius and start/end angles originating from a point feature.</p>


## Object Signature

```csharp
public class CIMGeometricEffectCircularSector : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectCircularSector()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Represents the circular sector geometric effect which creates a circular sector of a specified radius and start/end angles originating from a point feature.</p>


```csharp
public CIMGeometricEffectCircularSector()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectCircularSector.</p>


```csharp
public CIMGeometricEffectCircularSector Clone()
```
### EndAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Gets or sets the end angle of the circular sector. The angle is calculated in a counterclockwise manner with 0 degrees equal to due east.</p>


```csharp
public double EndAngle { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectCircularSector with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectCircularSector FromJson(string json, JsonDeserializationSettings settings = null)
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Gets or sets the radius of the circular sector.</p>


```csharp
public double Radius { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Gets or sets the start angle of the circular sector. The angle is calculated in a counterclockwise manner with 0 degrees equal to due east.</p>


```csharp
public double StartAngle { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectCircularSector and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCircularSector.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


