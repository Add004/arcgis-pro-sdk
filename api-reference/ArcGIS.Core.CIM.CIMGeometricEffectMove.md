# CIMGeometricEffectMove

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Represents the move geometric effect which creates a point, line or polygon that is offset a specified distance in X and Y.</p>


## Object Signature

```csharp
public class CIMGeometricEffectMove : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectMove()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Represents the move geometric effect which creates a point, line or polygon that is offset a specified distance in X and Y.</p>


```csharp
public CIMGeometricEffectMove()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectMove.</p>


```csharp
public CIMGeometricEffectMove Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectMove with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectMove FromJson(string json, JsonDeserializationSettings settings = null)
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Gets or sets the distance to move the symbol along the X-axis of the feature geometry.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Gets or sets the distance to move the symbol along the Y-axis of the feature geometry.</p>


```csharp
public double OffsetY { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectMove and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectMove.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


