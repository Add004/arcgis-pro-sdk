# NAODCostMatrixSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Represents an origin-destination cost matrix solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAODCostMatrixSolver : NASolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAODCostMatrixSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Represents an origin-destination cost matrix solver. This class is reserved for esri internal use only.</p>


```csharp
public NAODCostMatrixSolver()
```
### DateTimeSynchronizeUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time synchronize usage setting.</p>


```csharp
public esriNADateTimeSynchronizeUsage DateTimeSynchronizeUsage { get; set; }
```
### DefaultCutoff

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the default cutoff value to stop traversing.</p>


```csharp
public object DefaultCutoff { get; set; }
```
### DefaultTargetDestinationCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the default number of destinations to find.</p>


```csharp
public int DefaultTargetDestinationCount { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Reconstructs the NAODCostMatrixSolver with a specified state from a JSON encoding.</p>


```csharp
public static NAODCostMatrixSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### MatrixResultType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the type of matrix result to be created.</p>


```csharp
public esriNAODCostMatrixType MatrixResultType { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### PopulateODLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the ODLines class is to be populated.</p>


```csharp
public bool PopulateODLines { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeOfDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time value used in time-aware solvers.</p>


```csharp
public DateTime TimeOfDay { get; set; }
```
### TimeOfDayIsUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether TimeOfDay is in UTC.</p>


```csharp
public bool TimeOfDayIsUTC { get; set; }
```
### TimeOfDayUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Gets and sets the usage type for the TimeOfDay property.</p>


```csharp
public esriNATimeOfDayUsage TimeOfDayUsage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAODCostMatrixSolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAODCostMatrixSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


