# CIMGeometricEffectEnclosingPolygon

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Represents the enclosing polygon geometric effect which creates a dynamic polygon from the spatial extent of a line or polygon feature.</p>


## Object Signature

```csharp
public class CIMGeometricEffectEnclosingPolygon : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectEnclosingPolygon()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Represents the enclosing polygon geometric effect which creates a dynamic polygon from the spatial extent of a line or polygon feature.</p>


```csharp
public CIMGeometricEffectEnclosingPolygon()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectEnclosingPolygon.</p>


```csharp
public CIMGeometricEffectEnclosingPolygon Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectEnclosingPolygon with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectEnclosingPolygon FromJson(string json, JsonDeserializationSettings settings = null)
```
### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Gets or sets the method which specifies the way in which the polygon geometry is generated around the feature geometry.</p>


```csharp
public GeometricEffectEnclosingPolygonMethod Method { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectEnclosingPolygon and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectEnclosingPolygon.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


