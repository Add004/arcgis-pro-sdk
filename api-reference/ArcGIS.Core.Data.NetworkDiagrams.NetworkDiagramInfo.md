# NetworkDiagramInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.NetworkDiagrams.html">NetworkDiagrams</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Represents information about a <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class NetworkDiagramInfo
```


## Members

### Access

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramAccessType" data-throw-if-not-resolved="false"></xref> of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public NetworkDiagramAccessType Access { get; }
```
### AggregationCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the aggregation count of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int AggregationCount { get; }
```
### CanExtend

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Specifies whether the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> can be extended using <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.Extend(ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramExtendType)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool CanExtend { get; }
```
### CanStore

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Specifies whether the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> can be stored using <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram.Store(System.String%2cArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramAccessType%2cSystem.String)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool CanStore { get; }
```
### ContainerCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the container count of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int ContainerCount { get; }
```
### ContainerMargin

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the container margin of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double ContainerMargin { get; }
```
### CreationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the creation <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DateTime CreationDate { get; }
```
### Creator

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the name of the user who created the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string Creator { get; }
```
### DiagramExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the diagram extent <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Envelope DiagramExtent { get; }
```
### EdgeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the edge count of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int EdgeCount { get; }
```
### IsHistorical

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Specifies whether the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> is based on historical data.</p>


```csharp
public bool IsHistorical { get; }
```
### IsStored

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Specifies whether the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref> has been stored in the geodatabase.</p>


```csharp
public bool IsStored { get; }
```
### IsSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Specifies whether the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>
is a system-generated <xref href="ArcGIS.Core.Data.UtilityNetwork.Subnetwork" data-throw-if-not-resolved="false"></xref> diagram.</p>


```csharp
public bool IsSystem { get; }
```
### JunctionCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the junction count of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int JunctionCount { get; }
```
### LastUpdateBy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the name of the last user who made an update to the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string LastUpdateBy { get; }
```
### LastUpdateDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the <xref href="System.DateTime" data-throw-if-not-resolved="false"></xref> of the last update made to the <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DateTime LastUpdateDate { get; }
```
### NetworkExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the network extent <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Envelope NetworkExtent { get; }
```
### ReflexiveEdgeRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the reflexive edge radius of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double ReflexiveEdgeRadius { get; }
```
### Tag

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagramInfo.yml" sourcestartlinenumber="1">Gets the tag of the  <xref href="ArcGIS.Core.Data.NetworkDiagrams.NetworkDiagram" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string Tag { get; }
```


