# CIMChartTrajectoryProfileFeature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Represents the definition of a track or point for which data is to be plotted.</p>


## Object Signature

```csharp
public class CIMChartTrajectoryProfileFeature : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTrajectoryProfileFeature()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Represents the definition of a track or point for which data is to be plotted.</p>


```csharp
public CIMChartTrajectoryProfileFeature()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTrajectoryProfileFeature.</p>


```csharp
public CIMChartTrajectoryProfileFeature Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this feature is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTrajectoryProfileFeature with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTrajectoryProfileFeature FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Gets or sets the object ID of the track or point feature.</p>


```csharp
public long ID { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Gets or sets the feature label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Gets or sets the feature symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTrajectoryProfileFeature and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrajectoryID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Gets or sets a value indicating the trajectoryID for this feature.</p>


```csharp
public long TrajectoryID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileFeature.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


