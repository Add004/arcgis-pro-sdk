# CIMGeometricEffectTaperedPolygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Represents the tapered polygon geometric effect which creates a dynamic polygon along a line feature, whose width varies by two specified amounts along its length, as defined by a percentage of the line feature's length.</p>


## Object Signature

```csharp
public class CIMGeometricEffectTaperedPolygon : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectTaperedPolygon()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Represents the tapered polygon geometric effect which creates a dynamic polygon along a line feature, whose width varies by two specified amounts along its length, as defined by a percentage of the line feature's length.</p>


```csharp
public CIMGeometricEffectTaperedPolygon()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectTaperedPolygon.</p>


```csharp
public CIMGeometricEffectTaperedPolygon Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectTaperedPolygon with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectTaperedPolygon FromJson(string json, JsonDeserializationSettings settings = null)
```
### FromWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Gets or sets the width at the start of the line to be used to generate a polygon.</p>


```csharp
public double FromWidth { get; set; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Gets or sets the distance along the line to be used to generate the polygon.</p>


```csharp
public double Length { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectTaperedPolygon and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Gets or sets the width at the end of the line to be used to generate the polygon.</p>


```csharp
public double ToWidth { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectTaperedPolygon.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


