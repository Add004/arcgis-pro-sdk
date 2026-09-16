# CIMGeometricEffectRegularPolygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Represents the regular polygon geometric effect which creates a dynamic polygon around a point feature with a specified number of edges. All edges are equal in length and all angles are equal.</p>


## Object Signature

```csharp
public class CIMGeometricEffectRegularPolygon : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectRegularPolygon()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Represents the regular polygon geometric effect which creates a dynamic polygon around a point feature with a specified number of edges. All edges are equal in length and all angles are equal.</p>


```csharp
public CIMGeometricEffectRegularPolygon()
```
### Angle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Gets or sets the amount of rotation for the polygon.</p>


```csharp
public double Angle { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectRegularPolygon.</p>


```csharp
public CIMGeometricEffectRegularPolygon Clone()
```
### Edges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Gets or sets the number of sides for the polygon. Specifying a value less than 3 produces a circle.</p>


```csharp
public int Edges { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectRegularPolygon with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectRegularPolygon FromJson(string json, JsonDeserializationSettings settings = null)
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Gets or sets the distance from the center of the polygon.</p>


```csharp
public double Radius { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectRegularPolygon and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectRegularPolygon.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


