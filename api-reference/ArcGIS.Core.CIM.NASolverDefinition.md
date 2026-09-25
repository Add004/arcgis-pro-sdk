# NASolverDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Represents a solver definition. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public abstract class NASolverDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NASolverDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Represents a solver definition. This class is reserved for esri internal use only.</p>


```csharp
protected NASolverDefinition()
```
### AccumulateAttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the accumulate attribute names.</p>


```csharp
public string[] AccumulateAttributeNames { get; set; }
```
### AppliedTravelMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the applied travel mode.</p>


```csharp
public NetworkTravelMode AppliedTravelMode { get; set; }
```
### AppliedTravelModeJSON

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the applied travel mode as JSON.</p>


```csharp
public string AppliedTravelModeJSON { get; }
```
### AttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the attribute names.</p>


```csharp
public string[] AttributeNames { get; }
```
### AttributeParameterValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the attribute parameters values.</p>


```csharp
public NAAttributeParameterValue[] AttributeParameterValues { get; }
```
### HierarchyAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the name of the hierarchy attribute to be used in analysis.</p>


```csharp
public string HierarchyAttributeName { get; }
```
### HierarchyLevelCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the hierarchy level count.</p>


```csharp
public int HierarchyLevelCount { get; }
```
### HierarchyMaxValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the maximum value of the hierarchy attribute.</p>


```csharp
public int[] HierarchyMaxValues { get; }
```
### HierarchyNumTransitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the number of lower level junctions to explore before searching the next hierarchy level.</p>


```csharp
public int[] HierarchyNumTransitions { get; }
```
### IgnoreInvalidLocations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates whether or not to ignore invalid locations.</p>


```csharp
public bool IgnoreInvalidLocations { get; set; }
```
### ImpedanceAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the impedance attribute name.</p>


```csharp
public string ImpedanceAttributeName { get; }
```
### NetworkBuildHash

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the associated network build hash.</p>


```csharp
public int NetworkBuildHash { get; set; }
```
### OutputGeometryPrecision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the output geometry precision.</p>


```csharp
public object OutputGeometryPrecision { get; }
```
### OutputGeometryPrecisionUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the output geometry precision units.</p>


```csharp
public esriUnits OutputGeometryPrecisionUnits { get; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ResetHierarchyRangesOnBind

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the hierarchy ranges will be reset to the network dataset's hierarchy settings when the solver is bound.</p>


```csharp
public bool ResetHierarchyRangesOnBind { get; }
```
### RestrictUTurns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets a setting which indicates how U-Turns should be restricted in the analysis.</p>


```csharp
public esriNetworkForwardStarBacktrack RestrictUTurns { get; }
```
### RestrictionAttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the restriction attribute names.</p>


```csharp
public string[] RestrictionAttributeNames { get; }
```
### SolverOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the associated solver overrides.</p>


```csharp
public Dictionary<string, object> SolverOverrides { get; set; }
```
### UseHierarchy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the hierarchy attribute for the network should be used in analysis.</p>


```csharp
public bool UseHierarchy { get; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NASolverDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


