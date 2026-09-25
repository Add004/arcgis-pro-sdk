# CIMGeometricEffectRotate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Represents the rotate geometric effect which creates a dynamic line or polygon rotated a specified angle from the feature.</p>


## Object Signature

```csharp
public class CIMGeometricEffectRotate : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectRotate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Represents the rotate geometric effect which creates a dynamic line or polygon rotated a specified angle from the feature.</p>


```csharp
public CIMGeometricEffectRotate()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Gets or sets the amount of rotation for the symbol.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectRotate.</p>


```csharp
public CIMGeometricEffectRotate Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectRotate with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectRotate FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectRotate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRotate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


