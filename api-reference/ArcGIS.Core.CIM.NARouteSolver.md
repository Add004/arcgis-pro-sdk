# NARouteSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Represents a route solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NARouteSolver : NADirectionsCapableSolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NARouteSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Represents a route solver. This class is reserved for esri internal use only.</p>


```csharp
public NARouteSolver()
```
### CreateTraversalResult

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if a traversal result will be generated.</p>


```csharp
public bool CreateTraversalResult { get; set; }
```
### DateTimeSynchronizeUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time synchronize usage setting.</p>


```csharp
public esriNADateTimeSynchronizeUsage DateTimeSynchronizeUsage { get; set; }
```
### FindBestSequence

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the solver should resequence the route in the optimal order.</p>


```csharp
public bool FindBestSequence { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Reconstructs the NARouteSolver with a specified state from a JSON encoding.</p>


```csharp
public static NARouteSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputDateTimeFieldsAreUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether the input date time fields are in UTC.</p>


```csharp
public bool InputDateTimeFieldsAreUTC { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets the output line type.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### PreserveFirstStop

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the solver should keep the first stop fixed in the sequence.</p>


```csharp
public bool PreserveFirstStop { get; set; }
```
### PreserveLastStop

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the solver should keep the last stop fixed in the sequence.</p>


```csharp
public bool PreserveLastStop { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets the time the route begins.</p>


```csharp
public DateTime StartTime { get; set; }
```
### TimeOfDayIsUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether TimeOfDay is in UTC.</p>


```csharp
public bool TimeOfDayIsUTC { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NARouteSolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseStartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the solver should start the route at a particular time.</p>


```csharp
public bool UseStartTime { get; set; }
```
### UseTimeWindows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the solver should consider time windows.</p>


```csharp
public bool UseTimeWindows { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NARouteSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


