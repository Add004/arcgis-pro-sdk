# CIMGeometricEffectSuppress

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Represents the suppress geometric effect which creates a dynamic line that hides sections of a stroke between pairs control points.</p>


## Object Signature

```csharp
public class CIMGeometricEffectSuppress : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectSuppress()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Represents the suppress geometric effect which creates a dynamic line that hides sections of a stroke between pairs control points.</p>


```csharp
public CIMGeometricEffectSuppress()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectSuppress.</p>


```csharp
public CIMGeometricEffectSuppress Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectSuppress with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectSuppress FromJson(string json, JsonDeserializationSettings settings = null)
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to invert the suppression process. If this value is true, portions of the stroke symbol between control points are kept and all other portions are suppressed.</p>


```csharp
public bool Invert { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Suppress

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the portion of the stroke symbol between control points should be suppressed. Sections that are suppressed draw with no symbol.</p>


```csharp
public bool Suppress { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectSuppress and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectSuppress.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


