# CIMStandaloneVideo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Represents a standalone video.</p>


## Object Signature

```csharp
public class CIMStandaloneVideo : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandaloneVideo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Represents a standalone video.</p>


```csharp
public CIMStandaloneVideo()
```
### BookmarkIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of event indicators for Bookmark.</p>


```csharp
public CIMVideoTimelineEventIndicator[] BookmarkIndicators { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandaloneVideo.</p>


```csharp
public CIMStandaloneVideo Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the data connection for the video.</p>


```csharp
public CIMVideoDataConnection DataConnection { get; set; }
```
### ElapsedTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the elapsed time in seconds.</p>


```csharp
public double ElapsedTime { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the standalone video is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### ExportFrameIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of event indicators for ExportFrame.</p>


```csharp
public CIMVideoTimelineEventIndicator[] ExportFrameIndicators { get; set; }
```
### ExportFramesIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of range indicators for ExportFrames.</p>


```csharp
public CIMVideoTimelineRangeIndicator[] ExportFramesIndicators { get; set; }
```
### ExportSegmentIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of range indicators for ExportSegment.</p>


```csharp
public CIMVideoTimelineRangeIndicator[] ExportSegmentIndicators { get; set; }
```
### ExportToPPTIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of event indicators for ExportToPPT.</p>


```csharp
public CIMVideoTimelineEventIndicator[] ExportToPPTIndicators { get; set; }
```
### FootprintColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the footprint color.</p>


```csharp
public CIMColor FootprintColor { get; set; }
```
### FrameCenterGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the graphic element representing the frame center.</p>


```csharp
public CIMVideoGraphicElement FrameCenterGraphic { get; set; }
```
### FrameOutlineGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the graphic element representing the frame outline.</p>


```csharp
public CIMVideoGraphicElement FrameOutlineGraphic { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Reconstructs the CIMStandaloneVideo with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandaloneVideo FromJson(string json, JsonDeserializationSettings settings = null)
```
### MetadataToCSVIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of range indicators for MetadataToCSV.</p>


```csharp
public CIMVideoTimelineRangeIndicator[] MetadataToCSVIndicators { get; set; }
```
### PlatformPositionGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the graphic element representing the platform position.</p>


```csharp
public CIMVideoGraphicElement PlatformPositionGraphic { get; set; }
```
### PlatformTrailGraphic

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the graphic element representing the platform trail.</p>


```csharp
public CIMVideoGraphicElement PlatformTrailGraphic { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RecordSegmentsIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of range indicators for RecordSegments.</p>


```csharp
public CIMVideoTimelineRangeIndicator[] RecordSegmentsIndicators { get; set; }
```
### RecordVideoIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of range indicators for RecordVideo.</p>


```csharp
public CIMVideoTimelineRangeIndicator[] RecordVideoIndicators { get; set; }
```
### SelectedKLVChannels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets the collection of selected Key-Length-Value (KLV) channels.</p>


```csharp
public int[] SelectedKLVChannels { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandaloneVideo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the standalone video graphics is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneVideo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


