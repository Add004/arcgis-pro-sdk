# CIMVoxelStretchRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Represents a stretch renderer.</p>


## Object Signature

```csharp
public class CIMVoxelStretchRenderer : CIMVoxelRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelStretchRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Represents a stretch renderer.</p>


```csharp
public CIMVoxelStretchRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelStretchRenderer.</p>


```csharp
public CIMVoxelStretchRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp of the renderer.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ColorRangeMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double ColorRangeMax { get; set; }
```
### ColorRangeMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum value.</p>


```csharp
public double ColorRangeMin { get; set; }
```
### DataFilterMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double DataFilterMax { get; set; }
```
### DataFilterMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum value.</p>


```csharp
public double DataFilterMin { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelStretchRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelStretchRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### Interpolation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the interpolation mode.</p>


```csharp
public VoxelInterpolationMode Interpolation { get; set; }
```
### IsDataFilterEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether data filter is enabled.</p>


```csharp
public bool IsDataFilterEnabled { get; set; }
```
### MaxLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label for the maximum color range value.</p>


```csharp
public string MaxLabel { get; set; }
```
### MinLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label for the minimum color range value.</p>


```csharp
public string MinLabel { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowFullDataRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the histogram shows the full data range.</p>


```csharp
public bool ShowFullDataRange { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelStretchRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransparencyStopPositions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the transparency stop positions.</p>


```csharp
public double[] TransparencyStopPositions { get; set; }
```
### TransparencyStopValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets the transparency stop values.</p>


```csharp
public double[] TransparencyStopValues { get; set; }
```
### UseTransparencyStops

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether transparency stops are used.</p>


```csharp
public bool UseTransparencyStops { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelStretchRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


