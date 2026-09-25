# CIMFilteredFindPathsConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths Configuration.</p>


## Object Signature

```csharp
public class CIMFilteredFindPathsConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFilteredFindPathsConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Filtered Find Paths Configuration.</p>


```csharp
public CIMFilteredFindPathsConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFilteredFindPathsConfiguration.</p>


```csharp
public CIMFilteredFindPathsConfiguration Clone()
```
### ClosedPathPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the closed path policy, i.e whether we allow, forbid, or require that
the start and end vertices of a path are equal.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="4">When the value is KGClosedPathPolicy.Require, the DestinationEntities field is ignored
and destinations entities are the same as origin entities.</p>


```csharp
public KGClosedPathPolicy ClosedPathPolicy { get; set; }
```
### DefaultRelationshipCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the default relationship cost.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="3">If the default relationship cost is negative, it is replaced by zero.</p>


```csharp
public double DefaultRelationshipCost { get; set; }
```
### DefaultTraversalDirectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the default traversal direction which is used for any relationship type that is not defined in the traversal directions list.</p>


```csharp
public KGTraversalDirectionType DefaultTraversalDirectionType { get; set; }
```
### DestinationEntities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the destination entities.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="3">This field is ignored when ClosedPathPolicy is KGClosedPathPolicy.Require.</p>


```csharp
public CIMFilteredFindPathsEntity[] DestinationEntities { get; set; }
```
### EntityUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the usage of origin/destination entities in the filtered find paths algorithm.</p>


```csharp
public FilteredFindPathsEntityUsage EntityUsage { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMFilteredFindPathsConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMFilteredFindPathsConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxCountPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the max number of paths the filtered find paths algorithm returns.
This parameter is only taken into account when PathMode is KGPathMode.All.</p>


```csharp
public int MaxCountPaths { get; set; }
```
### MaxPathCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the maximum path cost.
The maximum cost is only enforced when the value is positive.</p>


```csharp
public double MaxPathCost { get; set; }
```
### MaxPathLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the maximum path length.
The default of 0 means the value is unlimited.</p>


```csharp
public int MaxPathLength { get; set; }
```
### MinPathCost

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the minimum path cost.</p>


```csharp
public double MinPathCost { get; set; }
```
### MinPathLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the minimum path length.</p>


```csharp
public int MinPathLength { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the name of the configuration.</p>


```csharp
public string Name { get; set; }
```
### NegativeCostBehaviour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the behaviour when a negative cost is found.</p>


```csharp
public KGNegativeCostBehaviour NegativeCostBehaviour { get; set; }
```
### OriginEntities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the origin entities.</p>


```csharp
public CIMFilteredFindPathsEntity[] OriginEntities { get; set; }
```
### PathFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the path filters.</p>


```csharp
public CIMFilteredFindPathsPathFilter[] PathFilters { get; set; }
```
### PathMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets whether the filtered find paths algorithm searches for shortest paths, for lowest cost paths or for all paths.</p>


```csharp
public KGPathMode PathMode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipCostProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the name of the property representing the cost of a relationship.
If a relationship lacks this property, the property is not of a numeric type,
or the property value is null, the cost of the relationship will be
<xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.DefaultRelationshipCost" data-throw-if-not-resolved="false"></xref>.
Only positive costs are supported. Any strictly negative cost will be converted to a positive cost based on
<xref href="ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.NegativeCostBehaviour" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string RelationshipCostProperty { get; set; }
```
### TimeFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the time filter.</p>


```csharp
public CIMKGTimeFilter TimeFilter { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFilteredFindPathsConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TraversalDirections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Gets or sets the traversal directions.</p>


```csharp
public CIMKGTraversalDirection[] TraversalDirections { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


