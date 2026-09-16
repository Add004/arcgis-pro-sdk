# NAServiceAreaSolver

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Represents a service area solver. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAServiceAreaSolver : NASolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAServiceAreaSolver()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Represents a service area solver. This class is reserved for esri internal use only.</p>


```csharp
public NAServiceAreaSolver()
```
### CreateTraversalResult

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if a traversal result is created.</p>


```csharp
public bool CreateTraversalResult { get; set; }
```
### DateTimeSynchronizeUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time synchronize usage setting.</p>


```csharp
public esriNADateTimeSynchronizeUsage DateTimeSynchronizeUsage { get; set; }
```
### DefaultBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the default breaks.</p>


```csharp
public double[] DefaultBreaks { get; set; }
```
### ExcludeSourcesFromPolygons

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a collection of network source names to NOT use when generating polygons.</p>


```csharp
public string[] ExcludeSourcesFromPolygons { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Reconstructs the NAServiceAreaSolver with a specified state from a JSON encoding.</p>


```csharp
public static NAServiceAreaSolver FromJson(string json, JsonDeserializationSettings settings = null)
```
### IncludeSourceInformationOnLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the lines will have SourceID, SourceOID, from and to position information added.</p>


```csharp
public bool IncludeSourceInformationOnLines { get; set; }
```
### MergeSimilarPolygonRanges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if similar ranges should be merged in the result polygons.</p>


```csharp
public bool MergeSimilarPolygonRanges { get; set; }
```
### OutputLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriNAOutputLineType OutputLines { get; set; }
```
### OutputPolygons

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the type of polygon(s) generated.</p>


```csharp
public esriNAOutputPolygonType OutputPolygons { get; set; }
```
### OverlapLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if lines should overlap from multiple facilities.</p>


```csharp
public bool OverlapLines { get; set; }
```
### OverlapPolygons

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the polygons for all facilities should not overlap.</p>


```csharp
public bool OverlapPolygons { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SplitLinesAtBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if lines should be split at breaks.</p>


```csharp
public bool SplitLinesAtBreaks { get; set; }
```
### SplitPolygonsAtBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if polygons should be split at break values.</p>


```csharp
public bool SplitPolygonsAtBreaks { get; set; }
```
### TimeOfDay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the date-time value used in time-aware solvers.</p>


```csharp
public DateTime TimeOfDay { get; set; }
```
### TimeOfDayIsUTC

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether TimeOfDay is in UTC.</p>


```csharp
public bool TimeOfDayIsUTC { get; set; }
```
### TimeOfDayUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the usage type for the TimeOfDay property.</p>


```csharp
public esriNATimeOfDayUsage TimeOfDayUsage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAServiceAreaSolver and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TravelDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the travel direction.</p>


```csharp
public esriNATravelDirection TravelDirection { get; set; }
```
### TrimOuterPolygon

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the outermost polygon (at the maximum break value) will be trimmed.</p>


```csharp
public bool TrimOuterPolygon { get; set; }
```
### TrimPolygonDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the distance to trim if polygons are being trimmed.</p>


```csharp
public double TrimPolygonDistance { get; set; }
```
### TrimPolygonDistanceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Gets and sets the distance to trim distance units.</p>


```csharp
public esriUnits TrimPolygonDistanceUnits { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAServiceAreaSolver.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


