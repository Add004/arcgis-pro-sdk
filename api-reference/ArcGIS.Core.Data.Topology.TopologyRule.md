# TopologyRule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Represents a rule that has been defined for a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TopologyRule
```


## Members

### DestinationClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the name of the destination feature class to which this topology rule is assigned.</p>


```csharp
public string DestinationClass { get; }
```
### DestinationSubtype

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Subtype" data-throw-if-not-resolved="false"></xref> in the destination feature class to which this topology rule is assigned.
If it is not applicable, <code>null</code> is returned.</p>


```csharp
public Subtype DestinationSubtype { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the ID of this topology rule.</p>


```csharp
public int ID { get; }
```
### OriginClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the name of the origin feature class to which this topology rule is assigned.</p>


```csharp
public string OriginClass { get; }
```
### OriginSubtype

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Subtype" data-throw-if-not-resolved="false"></xref> in the origin feature class to which this topology rule is assigned.  If it is
not applicable, <code>null</code> is returned.</p>


```csharp
public Subtype OriginSubtype { get; }
```
### RuleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.TopologyRule.yml" sourcestartlinenumber="1">Gets the type of this topology rule.</p>


```csharp
public TopologyRuleType RuleType { get; }
```


