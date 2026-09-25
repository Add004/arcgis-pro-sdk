# CIMMarkerPlacementAlongLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Represents marker placement along the line which defines how a marker is placed along a line or polygon outline.</p>


## Object Signature

```csharp
public abstract class CIMMarkerPlacementAlongLine : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAlongLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Represents marker placement along the line which defines how a marker is placed along a line or polygon outline.</p>


```csharp
protected CIMMarkerPlacementAlongLine()
```
### CustomEndingOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Gets or sets where the pattern should end relative to the ending point of the geometry. The entire pattern is shifted along the line for the specified distance. Negative numbers shift to the left and positive numbers shift to the right. This is only applied if the Endings property is set to Custom.</p>


```csharp
public double CustomEndingOffset { get; set; }
```
### Endings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Gets or sets how markers are placed at the end points of a line.</p>


```csharp
public PlacementEndings Endings { get; set; }
```
### OffsetAlongLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Gets or sets where the pattern should begin relative to the starting point of the geometry. The entire pattern is shifted along the line for the specified distance. Negative numbers shift to the left and positive numbers shift to the right. This is only applied if the Endings property is set to No Constraint or Custom.</p>


```csharp
public double OffsetAlongLine { get; set; }
```
### PlacementTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Gets or sets the numeric pattern that defines the sequence of placed markers and the length of space between them.</p>


```csharp
public double[] PlacementTemplate { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


