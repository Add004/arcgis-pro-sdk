# NALastMileDeliverySolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Represents a last mile delivery fleet solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NALastMileDeliverySolver : NADirectionsCapableSolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALastMileDeliverySolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Represents a last mile delivery fleet solver. This class is reserved for esri internal use only.</p>


```csharp
public NALastMileDeliverySolver()
```
### AllDeliveryBeforePickup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets whether all deliveries are before pickups upon solve.</p>


```csharp
public bool AllDeliveryBeforePickup { get; set; }
```
### DistanceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the distance units.</p>


```csharp
public esriNetworkAttributeUnits DistanceUnits { get; set; }
```
### EarliestRouteStartDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the earliest route start date.</p>


```csharp
public DateOnly? EarliestRouteStartDate { get; set; }
```
### EarliestRouteStartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the earliest route start time.</p>


```csharp
public TimeOnly? EarliestRouteStartTime { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Reconstructs the NALastMileDeliverySolver with a specified state from a JSON encoding.</p>


```csharp
public static NALastMileDeliverySolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputDateTimeFieldsAreUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether the input date time fields are in UTC.</p>


```csharp
public bool InputDateTimeFieldsAreUTC { get; set; }
```
### MaxRouteTotalTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the route maximum total time span in time units.</p>


```csharp
public double? MaxRouteTotalTime { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SequenceGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the sequence gap inserted between assigned orders.</p>


```csharp
public int SequenceGap { get; set; }
```
### TimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Gets and sets the time units.</p>


```csharp
public esriNetworkAttributeUnits TimeUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALastMileDeliverySolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALastMileDeliverySolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


