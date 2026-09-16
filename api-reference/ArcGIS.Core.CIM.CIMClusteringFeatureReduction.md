# CIMClusteringFeatureReduction

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for reducing features by aggregating them into point clusters.</p>


## Object Signature

```csharp
public class CIMClusteringFeatureReduction : CIMAggregationFeatureReduction, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMClusteringFeatureReduction()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for reducing features by aggregating them into point clusters.</p>


```csharp
public CIMClusteringFeatureReduction()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Creates a deep copy of CIMClusteringFeatureReduction.</p>


```csharp
public CIMClusteringFeatureReduction Clone()
```
### ClusterRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the radius within which points are clustered. Units are points.</p>


```csharp
public double ClusterRadius { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Reconstructs the CIMClusteringFeatureReduction with a specified state from a JSON encoding.</p>


```csharp
public static CIMClusteringFeatureReduction FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the maximum scale. Beyond this scale, unclustered points will be shown.</p>


```csharp
public double MaximumScale { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMClusteringFeatureReduction and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visualization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the visualization used by the clusters.</p>


```csharp
public CIMAggregateVisualization Visualization { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClusteringFeatureReduction.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


