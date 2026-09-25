# CIMLayerElevationSurface

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Represents a layer elevation surface.</p>


## Object Signature

```csharp
public class CIMLayerElevationSurface : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerElevationSurface()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Represents a layer elevation surface.</p>


```csharp
public CIMLayerElevationSurface()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerElevationSurface.</p>


```csharp
public CIMLayerElevationSurface Clone()
```
### ElevationSurfaceLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Gets or sets the elevation surface layer URI.</p>


```csharp
public string ElevationSurfaceLayerURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerElevationSurface with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerElevationSurface FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsRelativeToScene

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the data relative to scene.</p>


```csharp
public bool IsRelativeToScene { get; set; }
```
### OffsetZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Gets or sets Z offset.</p>


```csharp
public double OffsetZ { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerElevationSurface and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerElevationSurface.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


