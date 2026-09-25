# CIMGeometricEffectLocalizerFeather

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Represents a geometric effect which creates a localizer feather for aeronautical charts.</p>


## Object Signature

```csharp
public class CIMGeometricEffectLocalizerFeather : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectLocalizerFeather()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Represents a geometric effect which creates a localizer feather for aeronautical charts.</p>


```csharp
public CIMGeometricEffectLocalizerFeather()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Gets or sets the angle of the localizer feather.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectLocalizerFeather.</p>


```csharp
public CIMGeometricEffectLocalizerFeather Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectLocalizerFeather with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectLocalizerFeather FromJson(string json, JsonDeserializationSettings settings = null)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Gets or sets the length of the localizer feather.</p>


```csharp
public double Length { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Style

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Gets or sets the localizer feather style.</p>


```csharp
public GeometricEffectLocalizerFeatherStyle Style { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectLocalizerFeather and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Gets or sets the width of the localizer feather.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectLocalizerFeather.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


