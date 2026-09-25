# CIMGeometricEffectOffset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Represents the offset geometric effect which creates a dynamic line or polygon offset at a specified distance perpendicularly from a feature.</p>


## Object Signature

```csharp
public class CIMGeometricEffectOffset : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectOffset()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Represents the offset geometric effect which creates a dynamic line or polygon offset at a specified distance perpendicularly from a feature.</p>


```csharp
public CIMGeometricEffectOffset()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectOffset.</p>


```csharp
public CIMGeometricEffectOffset Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectOffset with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectOffset FromJson(string json, JsonDeserializationSettings settings = null)
```
### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Gets or sets the way the strokes or fills are displayed at corners.</p>


```csharp
public GeometricEffectOffsetMethod Method { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Gets or sets the distance of the symbol perpendicular to the feature geometry.</p>


```csharp
public double Offset { get; set; }
```
### Option

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Gets or sets the way the symbol handles complex geometries.</p>


```csharp
public GeometricEffectOffsetOption Option { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectOffset and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffset.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


