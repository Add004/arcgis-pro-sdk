# RelationshipRuleDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.RelationshipRule" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RelationshipRuleDescription
```


## Members

### RelationshipRuleDescription(int?, int?)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RelationshipRule" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RelationshipRuleDescription(int? originSubtypeCode, int? destinationSubtypeCode)
```
### DestinationMaximumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The maximum cardinality range of the destination class for the rule.</p>


```csharp
public int DestinationMaximumCardinality { get; set; }
```
### DestinationMinimumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The minimum cardinality range of the destination class for the rule.</p>


```csharp
public int DestinationMinimumCardinality { get; set; }
```
### DestinationSubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The subtype code of the destination class for the rule.</p>


```csharp
public int? DestinationSubtypeCode { get; }
```
### OriginMaximumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The maximum cardinality range of the origin class for the rule.</p>


```csharp
public int OriginMaximumCardinality { get; set; }
```
### OriginMinimumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The minimum cardinality range of the origin class for the rule.</p>


```csharp
public int OriginMinimumCardinality { get; set; }
```
### OriginSubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RelationshipRuleDescription.yml" sourcestartlinenumber="1">The subtype code of the origin class for the rule.</p>


```csharp
public int? OriginSubtypeCode { get; }
```


