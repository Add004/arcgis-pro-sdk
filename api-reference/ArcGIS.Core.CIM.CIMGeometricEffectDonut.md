# CIMGeometricEffectDonut

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Represents the donut geometric effect which creates a dynamic polygon ring of a specified width in relation to the outline of polygon features.</p>


## Object Signature

```csharp
public class CIMGeometricEffectDonut : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectDonut()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Represents the donut geometric effect which creates a dynamic polygon ring of a specified width in relation to the outline of polygon features.</p>


```csharp
public CIMGeometricEffectDonut()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectDonut.</p>


```csharp
public CIMGeometricEffectDonut Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectDonut with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectDonut FromJson(string json, JsonDeserializationSettings settings = null)
```
### Method

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Gets or sets the method which specifies the way the strokes are displayed at convex corners of the polygon.</p>


```csharp
public GeometricEffectDonutMethod Method { get; set; }
```
### Option

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Gets or sets the option for the way the symbol handles complex geometries.</p>


```csharp
public GeometricEffectOffsetOption Option { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectDonut and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Gets or sets the distance from the edge of the polygon that the fill symbol is to be displayed.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDonut.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


