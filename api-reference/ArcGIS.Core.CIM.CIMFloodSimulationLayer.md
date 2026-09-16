# CIMFloodSimulationLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation layer.</p>


## Object Signature

```csharp
public class CIMFloodSimulationLayer : CIMSimulationLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation layer.</p>


```csharp
public CIMFloodSimulationLayer()
```
### CalibrationMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating the preset mode for the simulation layer.</p>


```csharp
public FloodSimulationCalibrationMode CalibrationMode { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationLayer.</p>


```csharp
public CIMFloodSimulationLayer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the color ramp for shading the water.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ContainWaterInAOI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether water is contained in the area of interest or allowed to leave through the edges.</p>


```csharp
public bool ContainWaterInAOI { get; set; }
```
### DEMSourceLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets an array of URIs for the layers that will contribute to the DEM for flood simulation.</p>


```csharp
public string[] DEMSourceLayers { get; set; }
```
### DisplayValueRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the display value range.</p>


```csharp
public CIMRange DisplayValueRange { get; set; }
```
### EvaporationRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the evaporation rate in millimeters per hour.</p>


```csharp
public double EvaporationRate { get; set; }
```
### FloodSimulationStorageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the simulation data storage that include water sources, barriers and culverts.</p>


```csharp
public string FloodSimulationStorageURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### InfiltrationMaxRaster

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the infiltration max raster.</p>


```csharp
public CIMFloodSimulationDepthRaster InfiltrationMaxRaster { get; set; }
```
### InfiltrationRateRaster

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the infiltration rate raster.</p>


```csharp
public CIMFloodSimulationRateRaster InfiltrationRateRaster { get; set; }
```
### InitialWaterDepthRaster

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the initial water depth raster.</p>


```csharp
public CIMFloodSimulationDepthRaster InitialWaterDepthRaster { get; set; }
```
### OverrideWeatherEffects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether weather effects are controlled by the simulation while playing.</p>


```csharp
public bool OverrideWeatherEffects { get; set; }
```
### RainfallDisplayUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the rainfall rate display units.</p>


```csharp
public LinearUnit RainfallDisplayUnits { get; set; }
```
### RainfallRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets an array of rainfall rates (in millimeters per hour) over durations (in seconds).</p>


```csharp
public CIMRateDuration[] RainfallRate { get; set; }
```
### RainfallTransitionTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the time (in seconds) to transition between rainfall rates.</p>


```csharp
public double RainfallTransitionTime { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SurfaceRoughnessValueRaster

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the roughness value raster.</p>


```csharp
public CIMFloodSimulationRateRaster SurfaceRoughnessValueRaster { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueRangeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the value range type for playing the simulation.</p>


```csharp
public FloodSimulationValueRangeType ValueRangeType { get; set; }
```
### WaterColorizer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the color class breaks for shading the water.</p>


```csharp
public CIMRasterClassifyColorizer WaterColorizer { get; set; }
```
### WaterDisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the water display type.</p>


```csharp
public FloodSimulationWaterDisplayType WaterDisplayType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


