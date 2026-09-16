# NAWasteCollectionSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Represents a waste collection fleet solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAWasteCollectionSolver : NADirectionsCapableSolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAWasteCollectionSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Represents a waste collection fleet solver. This class is reserved for esri internal use only.</p>


```csharp
public NAWasteCollectionSolver()
```
### AllowRouteConstraintViolations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets whether to allow route constraint violations upon solve.</p>


```csharp
public bool AllowRouteConstraintViolations { get; set; }
```
### DistanceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets the distance units.</p>


```csharp
public esriNetworkAttributeUnits DistanceUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Reconstructs the NAWasteCollectionSolver with a specified state from a JSON encoding.</p>


```csharp
public static NAWasteCollectionSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxRouteTotalTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets the route maximum total time span in time units.</p>


```csharp
public double? MaxRouteTotalTime { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RouteStartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets the route start time.</p>


```csharp
public TimeOnly? RouteStartTime { get; set; }
```
### StopCollectionMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets the stop collection mode.</p>


```csharp
public esriNACollectionMode? StopCollectionMode { get; set; }
```
### TimeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Gets and sets the time units.</p>


```csharp
public esriNetworkAttributeUnits TimeUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALastMileDeliverySolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAWasteCollectionSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


