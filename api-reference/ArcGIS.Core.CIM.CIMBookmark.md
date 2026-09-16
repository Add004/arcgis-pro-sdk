# CIMBookmark

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Represents a spatial bookmark.</p>


## Object Signature

```csharp
public class CIMBookmark : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBookmark()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Represents a spatial bookmark.</p>


```csharp
public CIMBookmark()
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the camera.</p>


```csharp
public CIMViewCamera Camera { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBookmark.</p>


```csharp
public CIMBookmark Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the bookmark description.</p>


```csharp
public string Description { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Reconstructs the CIMBookmark with a specified state from a JSON encoding.</p>


```csharp
public static CIMBookmark FromJson(string json, JsonDeserializationSettings settings = null)
```
### GroupName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the bookmark group name.</p>


```csharp
public string GroupName { get; set; }
```
### LayerRangeExtents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the layer range extents. Each layer range applies to a single map.</p>


```csharp
public CIMLayerRange[] LayerRangeExtents { get; set; }
```
### Location

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the location.</p>


```csharp
public Envelope Location { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the bookmark name.</p>


```csharp
public string Name { get; set; }
```
### RangeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the range extent. Can be used across multiple maps that share the same range name.
RangeExtent.LayerURI is not used.</p>


```csharp
public CIMLayerRange RangeExtent { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ThumbnailImagePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the thumbnail image path.</p>


```csharp
public string ThumbnailImagePath { get; set; }
```
### TimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the time extent.</p>


```csharp
public TimeExtent TimeExtent { get; set; }
```
### TimeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the time relation.</p>


```csharp
public esriTimeRelation TimeRelation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBookmark and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VideoElapsedTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the video elapsed time in seconds.</p>


```csharp
public double VideoElapsedTime { get; set; }
```
### VideoURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Gets or sets the URI to the standalone video.</p>


```csharp
public string VideoURI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmark.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


