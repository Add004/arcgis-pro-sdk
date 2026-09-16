# CIMGeometricEffectOffsetHatch

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Represents a geometric effect which creates a hatch pattern to depict special use airspace for aeronautical charts.</p>


## Object Signature

```csharp
public class CIMGeometricEffectOffsetHatch : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectOffsetHatch()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Represents a geometric effect which creates a hatch pattern to depict special use airspace for aeronautical charts.</p>


```csharp
public CIMGeometricEffectOffsetHatch()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectOffsetHatch.</p>


```csharp
public CIMGeometricEffectOffsetHatch Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectOffsetHatch with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectOffsetHatch FromJson(string json, JsonDeserializationSettings settings = null)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Gets or sets the length of the offset hatch.</p>


```csharp
public double Length { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Spacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Gets or sets the spacing of the offset hatch.</p>


```csharp
public double Spacing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectOffsetHatch and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectOffsetHatch.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


