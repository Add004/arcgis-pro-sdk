# RelationshipCardinality

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipCardinality.yml" sourcestartlinenumber="1">Specifies the number of rows in the origin table that can be related to a number of rows in the destination table.</p>


## Object Signature

```csharp
public enum RelationshipCardinality
```


## Members

### ManyToMany

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipCardinality.yml" sourcestartlinenumber="1">One origin row can relate to multiple destination rows and conversely, one destination row can relate to multiple origin rows.</p>


```csharp
ManyToMany = 3
```
### OneToMany

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipCardinality.yml" sourcestartlinenumber="1">One origin row can relate to multiple destination rows. In a OneToMany relationship, the origin table is always the one side and the many side must be the destination.</p>


```csharp
OneToMany = 2
```
### OneToOne

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipCardinality.yml" sourcestartlinenumber="1">One origin row can relate to only one destination row.</p>


```csharp
OneToOne = 1
```


