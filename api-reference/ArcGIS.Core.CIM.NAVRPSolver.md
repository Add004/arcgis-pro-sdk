# NAVRPSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Represents a vehicle routing problem solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAVRPSolver : NADirectionsCapableSolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAVRPSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Represents a vehicle routing problem solver. This class is reserved for esri internal use only.</p>


```csharp
public NAVRPSolver()
```
### CapacityCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the number of dimensions for object sizes.</p>


```csharp
public int CapacityCount { get; set; }
```
### DefaultDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the default date.</p>


```csharp
public DateTime DefaultDate { get; set; }
```
### DistanceFieldUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the distance field units.</p>


```csharp
public esriNetworkAttributeUnits DistanceFieldUnits { get; set; }
```
### ExcessTransitTimePenaltyFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the excess transit time penalty factor.</p>


```csharp
public double ExcessTransitTimePenaltyFactor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Reconstructs the NAVRPSolver with a specified state from a JSON encoding.</p>


```csharp
public static NAVRPSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputDateTimeFieldsAreUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether the input date time fields are in UTC.</p>


```csharp
public bool InputDateTimeFieldsAreUTC { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RouteSeedPointsDistancePenaltyFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the route seed points distance penalty factor.</p>


```csharp
public double RouteSeedPointsDistancePenaltyFactor { get; set; }
```
### RouteZonesDistancePenaltyFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the route zones distance penalty factor.</p>


```csharp
public double RouteZonesDistancePenaltyFactor { get; set; }
```
### SpatiallyClusterOrders

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets whether to spatially cluster orders.</p>


```csharp
public bool SpatiallyClusterOrders { get; set; }
```
### TimeFieldUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the time field units.</p>


```csharp
public esriNetworkAttributeUnits TimeFieldUnits { get; set; }
```
### TimeWindowViolationPenaltyFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Gets and sets the time window violation penalty factor.</p>


```csharp
public double TimeWindowViolationPenaltyFactor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAVRPSolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAVRPSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


