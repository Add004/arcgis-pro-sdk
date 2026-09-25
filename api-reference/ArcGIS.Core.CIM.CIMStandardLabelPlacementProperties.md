# CIMStandardLabelPlacementProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Represents standard label engine label placement properties.</p>


## Object Signature

```csharp
public class CIMStandardLabelPlacementProperties : CIMLabelPlacementProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandardLabelPlacementProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Represents standard label engine label placement properties.</p>


```csharp
public CIMStandardLabelPlacementProperties()
```
### AllowOverlappingLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow overlapping labels.</p>


```csharp
public bool AllowOverlappingLabels { get; set; }
```
### BufferRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the buffer ratio.</p>


```csharp
public double BufferRatio { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandardLabelPlacementProperties.</p>


```csharp
public CIMStandardLabelPlacementProperties Clone()
```
### FeatureWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the feature weight.</p>


```csharp
public StandardFeatureWeight FeatureWeight { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMStandardLabelPlacementProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandardLabelPlacementProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label weight.</p>


```csharp
public StandardLabelWeight LabelWeight { get; set; }
```
### LineLabelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the line label position.</p>


```csharp
public CIMStandardLineLabelPosition LineLabelPosition { get; set; }
```
### LineLabelPriorities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the line label priorities.</p>


```csharp
public CIMStandardLineLabelPriorities LineLabelPriorities { get; set; }
```
### LineOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the line offset.</p>


```csharp
public double LineOffset { get; set; }
```
### MaxDistanceFromTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum distance from target.</p>


```csharp
public double MaxDistanceFromTarget { get; set; }
```
### NumLabelsOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the option for number of labels.</p>


```csharp
public StandardNumLabelsOption NumLabelsOption { get; set; }
```
### PerpendicularToAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to place the label perpendicular to the angle.</p>


```csharp
public bool PerpendicularToAngle { get; set; }
```
### PlaceOnlyInsidePolygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to place the label only inside a polygon.</p>


```csharp
public bool PlaceOnlyInsidePolygon { get; set; }
```
### PointPlacementAngles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets an array of point placement angles.</p>


```csharp
public double[] PointPlacementAngles { get; set; }
```
### PointPlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the point placement method.</p>


```csharp
public StandardPointPlacementMethod PointPlacementMethod { get; set; }
```
### PointPlacementPriorities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the point placement priorities.</p>


```csharp
public CIMStandardPointPlacementPriorities PointPlacementPriorities { get; set; }
```
### PolygonPlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the polygon placement method.</p>


```csharp
public StandardPolygonPlacementMethod PolygonPlacementMethod { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the rotation field.</p>


```csharp
public string RotationField { get; set; }
```
### RotationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the rotation type.</p>


```csharp
public StandardLabelRotationType RotationType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandardLabelPlacementProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLabelPlacementProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


