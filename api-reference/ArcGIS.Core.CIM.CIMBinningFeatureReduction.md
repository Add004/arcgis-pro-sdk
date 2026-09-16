# CIMBinningFeatureReduction

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for reducing features by aggregating them into polygon bins.</p>


## Object Signature

```csharp
public class CIMBinningFeatureReduction : CIMAggregationFeatureReduction, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBinningFeatureReduction()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for reducing features by aggregating them into polygon bins.</p>


```csharp
public CIMBinningFeatureReduction()
```
### BinType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the bin type in which features are aggregated.</p>


```csharp
public esriFeatureBinType BinType { get; set; }
```
### ClientSideBinning

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether binning should be performed on the client side, even when the data source has binning capabilities.</p>


```csharp
public bool ClientSideBinning { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBinningFeatureReduction.</p>


```csharp
public CIMBinningFeatureReduction Clone()
```
### FeatureCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the number of features to use when <xref href="ArcGIS.Core.CIM.CIMBinningFeatureReduction.ThresholdType" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Core.CIM.BinsToPointsThresholdType.FeatureCount" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int FeatureCount { get; set; }
```
### FixedLevel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the bin level at which bins will be drawn. If -1, the bin level will be automatically chosen based on the minimum bin size.</p>


```csharp
public int FixedLevel { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Reconstructs the CIMBinningFeatureReduction with a specified state from a JSON encoding.</p>


```csharp
public static CIMBinningFeatureReduction FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the maximum scale to use when <xref href="ArcGIS.Core.CIM.CIMBinningFeatureReduction.ThresholdType" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Core.CIM.BinsToPointsThresholdType.MaxScale" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double MaximumScale { get; set; }
```
### MinimumBinSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the minimum size (in points) to maintain as the bins are drawn at different scales.</p>


```csharp
public double MinimumBinSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the spatial reference in which features are aggregated.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ThresholdType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the threshold at which points are shown.</p>


```csharp
public BinsToPointsThresholdType ThresholdType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBinningFeatureReduction and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visualization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the visualization used by the bins.</p>


```csharp
public CIMBinningVisualization Visualization { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningFeatureReduction.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


