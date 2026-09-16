# NALocationAllocationSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Represents a location-allocation solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NALocationAllocationSolver : NASolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALocationAllocationSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Represents a location-allocation solver. This class is reserved for esri internal use only.</p>


```csharp
public NALocationAllocationSolver()
```
### DateTimeSynchronizeUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time synchronize usage setting.</p>


```csharp
public esriNADateTimeSynchronizeUsage DateTimeSynchronizeUsage { get; set; }
```
### DefaultCapacity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the default capacity for each facility.</p>


```csharp
public double DefaultCapacity { get; set; }
```
### DefaultCutoff

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the default cutoff beyond which no demand point can be allocated to a facility</p>


```csharp
public object DefaultCutoff { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Reconstructs the NALocationAllocationSolver with a specified state from a JSON encoding.</p>


```csharp
public static NALocationAllocationSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImpedanceTransformation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets which formula will modify the impedance.</p>


```csharp
public esriNAImpedanceTransformationType ImpedanceTransformation { get; set; }
```
### NumberFacilitiesToLocate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets how many facilities will be present in the solution.</p>


```csharp
public int NumberFacilitiesToLocate { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### ProblemType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets which location-allocation problem type to solve.</p>


```csharp
public esriNALocationAllocationProblemType ProblemType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TargetMarketSharePercentage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the minimum number of facilites that will be placed to obtain the target market share.</p>


```csharp
public double TargetMarketSharePercentage { get; set; }
```
### TimeOfDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time value used in time-aware solvers.</p>


```csharp
public DateTime TimeOfDay { get; set; }
```
### TimeOfDayIsUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether TimeOfDay is in UTC.</p>


```csharp
public bool TimeOfDayIsUTC { get; set; }
```
### TimeOfDayUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the usage type for the TimeOfDay property.</p>


```csharp
public esriNATimeOfDayUsage TimeOfDayUsage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALocationAllocationSolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransformationParameter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets the impedance transformation parameter.</p>


```csharp
public double TransformationParameter { get; set; }
```
### TravelDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Gets and sets which direction the network will be traversed.</p>


```csharp
public esriNATravelDirection TravelDirection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocationAllocationSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


