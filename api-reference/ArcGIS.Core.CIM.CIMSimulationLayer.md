# CIMSimulationLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Provides access to properties of a simulation layer.</p>


## Object Signature

```csharp
public abstract class CIMSimulationLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSimulationLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Provides access to properties of a simulation layer.</p>


```csharp
protected CIMSimulationLayer()
```
### AreaOfInterest

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the area of interest.</p>


```csharp
public Polygon AreaOfInterest { get; set; }
```
### AreaOfInterestSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol for the area of interest.</p>


```csharp
public CIMPolygonSymbol AreaOfInterestSymbol { get; set; }
```
### CurrentTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the current time (in decimal hours) as an offset from the start of the simulation at which to start playing.</p>


```csharp
public double CurrentTime { get; set; }
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the simulation duration in decimal hours.</p>


```csharp
public double Duration { get; set; }
```
### ElevationDownscalingFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the downscaling factor for loading raster elevation tiles.
The cell size is multiplied by this value to change elevation level of detail.
The minimum value of 1 uses the most accurate elevation with the slowest performance.
Higher values increase the performance speed with less accurate elevation.</p>


```csharp
public double ElevationDownscalingFactor { get; set; }
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is the currently active simulation.</p>


```csharp
public bool IsActive { get; set; }
```
### ManualCellResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the manually set cell resolution in map units.</p>


```csharp
public double ManualCellResolution { get; set; }
```
### MaxAOIEdgeCellCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the maximum number of cells allowed on any edge of the area of interest.</p>


```csharp
public int MaxAOIEdgeCellCount { get; set; }
```
### PlaybackSpeed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the speed to play as a multiplier of the base speed.</p>


```csharp
public double PlaybackSpeed { get; set; }
```
### PlaybackStep

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the simulation playback time step in decimal hours.</p>


```csharp
public double PlaybackStep { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SecondsPerSimulationCacheSlice

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the amount of simulated time between cache slices in seconds. Only used when UseDefaultNumberOfCacheSlices is false.</p>


```csharp
public double SecondsPerSimulationCacheSlice { get; set; }
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets the simulation start time. The end time will be the start time plus the duration.</p>


```csharp
public TimeInstant StartTime { get; set; }
```
### UseAutomaticCellResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically determine the cell resolution.</p>


```csharp
public bool UseAutomaticCellResolution { get; set; }
```
### UseDefaultNumberOfCacheSlices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the default number of stored cache slices.</p>


```csharp
public bool UseDefaultNumberOfCacheSlices { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimulationLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


