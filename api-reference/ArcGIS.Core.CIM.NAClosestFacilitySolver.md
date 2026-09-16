# NAClosestFacilitySolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Represents a closest facility solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAClosestFacilitySolver : NADirectionsCapableSolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAClosestFacilitySolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Represents a closest facility solver. This class is reserved for esri internal use only.</p>


```csharp
public NAClosestFacilitySolver()
```
### CreateTraversalResult

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if a traversal result is created.</p>


```csharp
public bool CreateTraversalResult { get; set; }
```
### DateTimeSynchronizeUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the date-time synchronize usage setting.</p>


```csharp
public esriNADateTimeSynchronizeUsage DateTimeSynchronizeUsage { get; set; }
```
### DefaultCutoff

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the default cutoff value to stop traversing.</p>


```csharp
public object DefaultCutoff { get; set; }
```
### DefaultTargetFacilityCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the default number of facilities to find.</p>


```csharp
public int DefaultTargetFacilityCount { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Reconstructs the NAClosestFacilitySolver with a specified state from a JSON encoding.</p>


```csharp
public static NAClosestFacilitySolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeOfDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the date-time value used in time-aware solvers.</p>


```csharp
public DateTime TimeOfDay { get; set; }
```
### TimeOfDayIsUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether TimeOfDay is in UTC.</p>


```csharp
public bool TimeOfDayIsUTC { get; set; }
```
### TimeOfDayUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the usage type for the TimeOfDay property.</p>


```csharp
public esriNATimeOfDayUsage TimeOfDayUsage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAClosestFacilitySolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TravelDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Gets and sets the direction of the traversal.</p>


```csharp
public esriNATravelDirection TravelDirection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAClosestFacilitySolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


