# CIMElevationSurfaceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Represents an elevation surface layer.</p>


## Object Signature

```csharp
public class CIMElevationSurfaceLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMElevationSurfaceLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Represents an elevation surface layer.</p>


```csharp
public CIMElevationSurfaceLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMElevationSurfaceLayer.</p>


```csharp
public CIMElevationSurfaceLayer Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the surface color.</p>


```csharp
public CIMColor Color { get; set; }
```
### ElevationMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the elevation mode.</p>


```csharp
public ElevationMode ElevationMode { get; set; }
```
### ElevationSourceLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the sublayers.</p>


```csharp
public string[] ElevationSourceLayers { get; set; }
```
### EnableSurfaceShading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this elevation surface has shadows.</p>


```csharp
public bool EnableSurfaceShading { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMElevationSurfaceLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMElevationSurfaceLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SurfaceEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the surface effect definition for the elevation surface.</p>


```csharp
public CIMSurfaceEffect SurfaceEffect { get; set; }
```
### SurfaceTINShadingMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the elevation surface shading mode for TIN elevation sources.</p>


```csharp
public SurfaceTINShadingMode SurfaceTINShadingMode { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMElevationSurfaceLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSurfaceEffect

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current surface effect should be applied in 3D views.</p>


```csharp
public bool UseSurfaceEffect { get; set; }
```
### VerticalExaggeration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Gets or sets the vertical exaggeration.</p>


```csharp
public double VerticalExaggeration { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElevationSurfaceLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


