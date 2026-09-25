# CIMGeometricEffectReverse

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Represents the reverse geometric effect which creates a dynamic polygon around a point feature with a specified number of edges. All edges are equal in length and all angles are equal.</p>


## Object Signature

```csharp
public class CIMGeometricEffectReverse : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectReverse()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Represents the reverse geometric effect which creates a dynamic polygon around a point feature with a specified number of edges. All edges are equal in length and all angles are equal.</p>


```csharp
public CIMGeometricEffectReverse()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectReverse.</p>


```csharp
public CIMGeometricEffectReverse Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectReverse with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectReverse FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Reverse

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the dynamic output of a previous geometric effect is to be flipped or not.</p>


```csharp
public bool Reverse { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectReverse and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectReverse.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


