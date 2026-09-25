# TopologyError

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Represents an error associated with a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TopologyError
```


## Members

### DestinationClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the feature class name of the destination feature that created the topology error. If it is not applicable,
an empty string is returned.</p>


```csharp
public string DestinationClassName { get; }
```
### DestinationObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the object ID of the destination feature that created the topology error.</p>


```csharp
public long DestinationObjectID { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the ID of the topology error.</p>


```csharp
public long ID { get; }
```
### IsException

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets a value indicating whether this topology rule has been marked as an <b>exception</b>.</p>


```csharp
public bool IsException { get; }
```
### OriginClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the feature class name of the origin feature that created the topology error. If it is not applicable, an
empty string is returned.</p>


```csharp
public string OriginClassName { get; }
```
### OriginObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the object ID of the origin feature that created the topology error.</p>


```csharp
public long OriginObjectID { get; }
```
### RuleID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the ID of the topology rule being violated.</p>


```csharp
public int RuleID { get; }
```
### RuleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the type of topology rule being violated.</p>


```csharp
public TopologyRuleType RuleType { get; }
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyError.yml" sourcestartlinenumber="1">Gets the shape of the topology error.</p>


```csharp
public Geometry Shape { get; }
```


