# CIMMaplexLabelPlacementProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Represents Maplex label placement properties.</p>


## Object Signature

```csharp
public class CIMMaplexLabelPlacementProperties : CIMLabelPlacementProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexLabelPlacementProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Represents Maplex label placement properties.</p>


```csharp
public CIMMaplexLabelPlacementProperties()
```
### AlignLabelToLineDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to align the label with the label direction so the label may appear upside down.</p>


```csharp
public bool AlignLabelToLineDirection { get; set; }
```
### AllowAsymmetricOverrun

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a label may overrun one side of a polygon feature.</p>


```csharp
public bool AllowAsymmetricOverrun { get; set; }
```
### AllowStraddleStacking

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a stacked label may straddle the line feature.</p>


```csharp
public bool AllowStraddleStacking { get; set; }
```
### AlternateLabelExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the ExpressionInfo for the alternate label expression.</p>


```csharp
public CIMExpressionInfo AlternateLabelExpressionInfo { get; set; }
```
### AvoidOverlappingLabeledPolygonsAsIfHoles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether labels should avoid overlapping labeled polygons as if they were holes.</p>


```csharp
public bool AvoidOverlappingLabeledPolygonsAsIfHoles { get; set; }
```
### AvoidPolygonHoles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether labels should avoid holes in polygons.</p>


```csharp
public bool AvoidPolygonHoles { get; set; }
```
### BackgroundLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to place the label first and allow other labels to be placed over it.</p>


```csharp
public bool BackgroundLabel { get; set; }
```
### BoundaryLabelingAllowHoles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to allow holes in boundary labeling.</p>


```csharp
public bool BoundaryLabelingAllowHoles { get; set; }
```
### BoundaryLabelingAllowSingleSided

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to allow single sided boundary labeling.</p>


```csharp
public bool BoundaryLabelingAllowSingleSided { get; set; }
```
### BoundaryLabelingSingleSidedOnLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether single sided boundary label is centered on line.</p>


```csharp
public bool BoundaryLabelingSingleSidedOnLine { get; set; }
```
### CanAbbreviateLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to abbreviate the label using an abbreviation dictionary.</p>


```csharp
public bool CanAbbreviateLabel { get; set; }
```
### CanFlipStackedStreetLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a stacked label may be flipped over to obtain a better position.</p>


```csharp
public bool CanFlipStackedStreetLabel { get; set; }
```
### CanKeyNumberLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to key number the label and feature.</p>


```csharp
public bool CanKeyNumberLabel { get; set; }
```
### CanOverrunFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to place the label over end of line or over polygon boundary.</p>


```csharp
public bool CanOverrunFeature { get; set; }
```
### CanPlaceLabelOnTopOfFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the label can be placed on top of the street feature.</p>


```csharp
public bool CanPlaceLabelOnTopOfFeature { get; set; }
```
### CanPlaceLabelOutsidePolygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to place a label outside the polygon if it does not fit inside.</p>


```csharp
public bool CanPlaceLabelOutsidePolygon { get; set; }
```
### CanReduceFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to reduce the size of the font.</p>


```csharp
public bool CanReduceFontSize { get; set; }
```
### CanReduceLeading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the leading can be reduced for a stacked label.</p>


```csharp
public bool CanReduceLeading { get; set; }
```
### CanRemoveOverlappingLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to remove the label if it overlaps with other labels.</p>


```csharp
public bool CanRemoveOverlappingLabel { get; set; }
```
### CanShiftPointLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to allow the point label to be shifted upon a fixed position.</p>


```csharp
public bool CanShiftPointLabel { get; set; }
```
### CanStackLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to stack the label to obtain a better position.</p>


```csharp
public bool CanStackLabel { get; set; }
```
### CanTruncateLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to truncate the label using an algorithm.</p>


```csharp
public bool CanTruncateLabel { get; set; }
```
### CanUseAlternateLabelExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether an alternate label expression is allowed to be used.</p>


```csharp
public bool CanUseAlternateLabelExpression { get; set; }
```
### CenterLabelAnchorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets options to determine where to anchor a centered point label.</p>


```csharp
public MaplexCenterLabelAnchorType CenterLabelAnchorType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexLabelPlacementProperties.</p>


```csharp
public CIMMaplexLabelPlacementProperties Clone()
```
### ConnectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the options for connecting line features.</p>


```csharp
public MaplexConnectionType ConnectionType { get; set; }
```
### ConstrainOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label constraint options.</p>


```csharp
public MaplexConstrainOffset ConstrainOffset { get; set; }
```
### ContourAlignmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the options for the contour label alignment.</p>


```csharp
public MaplexContourAlignmentType ContourAlignmentType { get; set; }
```
### ContourLadderType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the options for the contour label ladder types.</p>


```csharp
public MaplexContourLadderType ContourLadderType { get; set; }
```
### ContourMaximumAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum angle at which a contour label may be placed.</p>


```csharp
public int ContourMaximumAngle { get; set; }
```
### DictionaryName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the abbreviations dictionary referenced by this layer.</p>


```csharp
public string DictionaryName { get; set; }
```
### EnableConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to turn off line connection.</p>


```csharp
public bool EnableConnection { get; set; }
```
### EnablePointPlacementPriorities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use user-defined point placement priorities.</p>


```csharp
public bool EnablePointPlacementPriorities { get; set; }
```
### EnablePolygonFixedPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a label is to be placed at a fixed position in the polygon.</p>


```csharp
public bool EnablePolygonFixedPosition { get; set; }
```
### EnableSecondaryOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to place a label at a secondary offset from the line feature.</p>


```csharp
public bool EnableSecondaryOffset { get; set; }
```
### FeatureWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the feature weight which controls which features may be overlapped and to what extent.</p>


```csharp
public int FeatureWeight { get; set; }
```
### FontHeightReductionLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets font height reduction limit. The font may be reduced in height until this limit is reached.</p>


```csharp
public double FontHeightReductionLimit { get; set; }
```
### FontHeightReductionStep

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets font height reduction step. This is the step interval for font height reduction.</p>


```csharp
public double FontHeightReductionStep { get; set; }
```
### FontWidthReductionLimit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets font width reduction limit. The font may be reduced in width until this limit is reached.</p>


```csharp
public double FontWidthReductionLimit { get; set; }
```
### FontWidthReductionStep

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets font width reduction step. This is the step interval for font width reduction.</p>


```csharp
public double FontWidthReductionStep { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexLabelPlacementProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexLabelPlacementProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GraticuleAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable graticule alignment.</p>


```csharp
public bool GraticuleAlignment { get; set; }
```
### GraticuleAlignmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the options for the graticule alignment type.</p>


```csharp
public MaplexGraticuleAlignmentType GraticuleAlignmentType { get; set; }
```
### IsLabelBufferHardConstraint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the label buffer is a hard constraint and must be honored.</p>


```csharp
public bool IsLabelBufferHardConstraint { get; set; }
```
### IsMinimumSizeBasedOnArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the minimum feature size for labeling is based on area.</p>


```csharp
public bool IsMinimumSizeBasedOnArea { get; set; }
```
### IsOffsetFromFeatureGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to measure the label offset from the feature geometry.</p>


```csharp
public bool IsOffsetFromFeatureGeometry { get; set; }
```
### KeyNumberGroupName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the key number group to use for key numbering the labels.</p>


```csharp
public string KeyNumberGroupName { get; set; }
```
### LabelBuffer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label buffer. Increase buffer to stop labels from being placed too close to each other.</p>


```csharp
public int LabelBuffer { get; set; }
```
### LabelLargestPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to label only the largest polygon in a compound polygon feature.</p>


```csharp
public bool LabelLargestPolygon { get; set; }
```
### LabelPriority

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label priority. Label priority controls approximate placement order.</p>


```csharp
public int LabelPriority { get; set; }
```
### LabelStackingProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label stacking properties for a layer.</p>


```csharp
public CIMMaplexLabelStackingProperties LabelStackingProperties { get; set; }
```
### LineFeatureType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the line feature type.</p>


```csharp
public MaplexLineFeatureType LineFeatureType { get; set; }
```
### LinePlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the line placement method.</p>


```csharp
public MaplexLinePlacementMethod LinePlacementMethod { get; set; }
```
### MaximumCharacterSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum character spacing. Character spacing may be increased up to this limit.</p>


```csharp
public double MaximumCharacterSpacing { get; set; }
```
### MaximumLabelOverrun

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum distance that a label is allowed to overrun the end of its feature.</p>


```csharp
public double MaximumLabelOverrun { get; set; }
```
### MaximumLabelOverrunUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label overrun unit.</p>


```csharp
public MaplexUnit MaximumLabelOverrunUnit { get; set; }
```
### MaximumWordSpacing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets maximum word spacing. The word spacing may be increased up to this limit.</p>


```csharp
public double MaximumWordSpacing { get; set; }
```
### MeasureFromClippedFeatureGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to measure the offset from the clipped feature geometry.
This property applies to label offsets when using the Along Line or Fixed Position Polygon placement methods.</p>


```csharp
public bool MeasureFromClippedFeatureGeometry { get; set; }
```
### MinimumEndOfStreetClearance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets minimum clearance between street label and street end.</p>


```csharp
public double MinimumEndOfStreetClearance { get; set; }
```
### MinimumFeatureSizeUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets minimum feature size unit.</p>


```csharp
public MaplexUnit MinimumFeatureSizeUnit { get; set; }
```
### MinimumRepetitionInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the interval that must elapse before label is repeated.</p>


```csharp
public double MinimumRepetitionInterval { get; set; }
```
### MinimumSizeForLabeling

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum size of a line or area feature for it to be labeled.</p>


```csharp
public double MinimumSizeForLabeling { get; set; }
```
### MultiPartOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the option for labeling multi-part shapes.</p>


```csharp
public MaplexMultiPartOption MultiPartOption { get; set; }
```
### NeverRemoveLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to not remove the label if no position is found.</p>


```csharp
public bool NeverRemoveLabel { get; set; }
```
### OffsetAlongLineProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the offset along line properties for a layer.</p>


```csharp
public CIMMaplexOffsetAlongLineProperties OffsetAlongLineProperties { get; set; }
```
### PointExternalZonePriorities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the properties which control placement of a label around point feature.</p>


```csharp
public CIMMaplexExternalZonePriorities PointExternalZonePriorities { get; set; }
```
### PointPlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the point placement method.</p>


```csharp
public MaplexPointPlacementMethod PointPlacementMethod { get; set; }
```
### PolygonAnchorPointPerimeterInset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the inset value for perimeter polygon anchor leader anchor points.</p>


```csharp
public double PolygonAnchorPointPerimeterInset { get; set; }
```
### PolygonAnchorPointPerimeterInsetUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the unit of the inset value for perimeter polygon anchor points.</p>


```csharp
public MaplexUnit PolygonAnchorPointPerimeterInsetUnit { get; set; }
```
### PolygonAnchorPointType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the polygon anchor point type.</p>


```csharp
public MaplexAnchorPointType PolygonAnchorPointType { get; set; }
```
### PolygonBoundaryWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the feature weight for the boundary of the polygon.</p>


```csharp
public int PolygonBoundaryWeight { get; set; }
```
### PolygonExternalZones

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the placement priorities associated with zones external to the polygon.</p>


```csharp
public CIMMaplexExternalZonePriorities PolygonExternalZones { get; set; }
```
### PolygonFeatureType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the polygon feature type.</p>


```csharp
public MaplexPolygonFeatureType PolygonFeatureType { get; set; }
```
### PolygonPlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the polygon placement method.</p>


```csharp
public MaplexPolygonPlacementMethod PolygonPlacementMethod { get; set; }
```
### PreferHorizontalPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether there is a preference to place the label horizontally.</p>


```csharp
public bool PreferHorizontalPlacement { get; set; }
```
### PreferLabelNearJunction

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether there is a preference for placing a line label near a junction.</p>


```csharp
public bool PreferLabelNearJunction { get; set; }
```
### PreferLabelNearJunctionClearance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the preferred clearance for placing a line label near a junction.</p>


```csharp
public double PreferLabelNearJunctionClearance { get; set; }
```
### PreferLabelNearMapBorder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether there is a preference for placing a line label near the map border.</p>


```csharp
public bool PreferLabelNearMapBorder { get; set; }
```
### PreferLabelNearMapBorderClearance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the preferred clearance for placing a line label near the map border.</p>


```csharp
public double PreferLabelNearMapBorderClearance { get; set; }
```
### PreferredEndOfStreetClearance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the preferred clearance between street label and street end.</p>


```csharp
public double PreferredEndOfStreetClearance { get; set; }
```
### PrimaryOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the primary offset between label and symbol.</p>


```csharp
public double PrimaryOffset { get; set; }
```
### PrimaryOffsetUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the unit of the primary offset.</p>


```csharp
public MaplexUnit PrimaryOffsetUnit { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RemoveAmbiguousLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the method to determine when to remove ambiguous labels.</p>


```csharp
public MaplexRemoveAmbiguousLabelsType RemoveAmbiguousLabels { get; set; }
```
### RemoveExtraLineBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether extra line breaks are removed from the label text.</p>


```csharp
public bool RemoveExtraLineBreaks { get; set; }
```
### RemoveExtraWhiteSpace

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether extra white space characters are removed from the label text.</p>


```csharp
public bool RemoveExtraWhiteSpace { get; set; }
```
### RepeatLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable the repetition of label along line feature.</p>


```csharp
public bool RepeatLabel { get; set; }
```
### RepetitionIntervalUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label repetition interval unit.</p>


```csharp
public MaplexUnit RepetitionIntervalUnit { get; set; }
```
### RotationProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the label rotation properties.</p>


```csharp
public CIMMaplexRotationProperties RotationProperties { get; set; }
```
### SecondaryOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the secondary offset between label and symbol.</p>


```csharp
public double SecondaryOffset { get; set; }
```
### SecondaryOffsetMaximum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the secondary offset maximum.</p>


```csharp
public double SecondaryOffsetMaximum { get; set; }
```
### SecondaryOffsetMinimum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the secondary offset minimum.</p>


```csharp
public double SecondaryOffsetMinimum { get; set; }
```
### SecondaryOffsetUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the unit of the secondary offset.</p>


```csharp
public MaplexUnit SecondaryOffsetUnit { get; set; }
```
### SpreadCharacters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to spread label characters along line features.</p>


```csharp
public bool SpreadCharacters { get; set; }
```
### SpreadWords

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to whether to spread words along line features.</p>


```csharp
public bool SpreadWords { get; set; }
```
### StrategyPriorities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the priority of a placement strategy when placing text.</p>


```csharp
public CIMMaplexStrategyPriorities StrategyPriorities { get; set; }
```
### ThinDuplicateLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to remove duplicate labels that lie within a specified distance of each other.</p>


```csharp
public bool ThinDuplicateLabels { get; set; }
```
### ThinningDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the distance used to control the thinning of duplicate labels.</p>


```csharp
public double ThinningDistance { get; set; }
```
### ThinningDistanceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the thinning distance unit.</p>


```csharp
public MaplexUnit ThinningDistanceUnit { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexLabelPlacementProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TruncationExcludedCharacters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the excluded characters used by the truncation strategy. These characters will never be removed by truncation.</p>


```csharp
public string TruncationExcludedCharacters { get; set; }
```
### TruncationMarkerCharacter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the marker character used by the truncation strategy.</p>


```csharp
public string TruncationMarkerCharacter { get; set; }
```
### TruncationMinimumLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum length of a label used by the truncation strategy.</p>


```csharp
public int TruncationMinimumLength { get; set; }
```
### TruncationPreferredCharacters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the preferred characters used by the truncation strategy. These characters will be removed as needed.</p>


```csharp
public string TruncationPreferredCharacters { get; set; }
```
### UseExactSymbolOutline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the exact polygon outline of a symbol when measuring the label offset.</p>


```csharp
public bool UseExactSymbolOutline { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelPlacementProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


