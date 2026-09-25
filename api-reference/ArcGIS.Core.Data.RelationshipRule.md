# RelationshipRule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">Represents a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> rule.</p>


## Object Signature

```csharp
public sealed class RelationshipRule
```


## Members

### DestinationClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The name of the destination class.</p>


```csharp
public string DestinationClassName { get; }
```
### DestinationMaximumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The maximum cardinality range of the destination class if the relationship class is many-to-many or one-to-many.</p>


```csharp
public int DestinationMaximumCardinality { get; }
```
### DestinationMinimumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The minimum cardinality range of the destination class if the relationship class is many-to-many or one-to-many.</p>


```csharp
public int DestinationMinimumCardinality { get; }
```
### DestinationSubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The subtype code of the destination class.</p>


```csharp
public int? DestinationSubtypeCode { get; }
```
### OriginClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The name of the origin class.</p>


```csharp
public string OriginClassName { get; }
```
### OriginMaximumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The maximum cardinality range of the origin class if the relationship class is many-to-many or one-to-many.</p>


```csharp
public int OriginMaximumCardinality { get; }
```
### OriginMinimumCardinality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The minimum cardinality range of the origin class if the relationship class is many-to-many or one-to-many.</p>


```csharp
public int OriginMinimumCardinality { get; }
```
### OriginSubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipRule.yml" sourcestartlinenumber="1">The subtype code of the origin class.</p>


```csharp
public int? OriginSubtypeCode { get; }
```


