# CIMMarkerPlacementAlongLineVariableSize

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Represents marker placement along the line which places markers in either increasing, decreasing or alternating gradations along a line or polygon outline.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAlongLineVariableSize : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAlongLineVariableSize()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Represents marker placement along the line which places markers in either increasing, decreasing or alternating gradations along a line or polygon outline.</p>


```csharp
public CIMMarkerPlacementAlongLineVariableSize()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAlongLineVariableSize.</p>


```csharp
public CIMMarkerPlacementAlongLineVariableSize Clone()
```
### ControlPointPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets how markers are placed at control points.</p>


```csharp
public SimplePlacementEndings ControlPointPlacement { get; set; }
```
### Endings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets how markers are placed at the end points of a line.</p>


```csharp
public SimplePlacementEndings Endings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAlongLineVariableSize with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAlongLineVariableSize FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxRandomOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the maximum random offset.</p>


```csharp
public double MaxRandomOffset { get; set; }
```
### MaxZoom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the largest size of the marker to be placed on the line. The value is expressed as a ratio.</p>


```csharp
public double MaxZoom { get; set; }
```
### MinZoom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the smallest size of the marker to be placed on the line. The value is expressed as a ratio.</p>


```csharp
public double MinZoom { get; set; }
```
### NumberOfSizes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the number of different sizes of markers to be placed on the line.</p>


```csharp
public int NumberOfSizes { get; set; }
```
### PlacementTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the numeric pattern that defines the sequence of placed markers and the length of space between them.</p>


```csharp
public double[] PlacementTemplate { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the starting value for generating a random number. This random number is used by the Randomization property to determine which size a marker will receive. This is only used if the VariationMethod is set to Random.</p>


```csharp
public int Seed { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAlongLineVariableSize and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Gets or sets the order in which the change of size in the markers should occur.</p>


```csharp
public SizeVariationMethod VariationMethod { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineVariableSize.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


