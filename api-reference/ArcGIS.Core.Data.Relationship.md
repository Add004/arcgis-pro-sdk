# Relationship

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Relationship.yml" sourcestartlinenumber="1">Represents a pair of related rows (or features) from a geodatabase.</p>


## Object Signature

```csharp
public class Relationship : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Relationship.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Data.Relationship" data-throw-if-not-resolved="false"></xref> represents a relationship between rows and/or features where the tables or feature classes
must participate in a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>. In this type of relationship, there is no intermediate table
to store information about the related rows/features.
Relationships are created using <xref href="ArcGIS.Core.Data.RelationshipClass.CreateRelationship(ArcGIS.Core.Data.Row%2cArcGIS.Core.Data.Row)" data-throw-if-not-resolved="false"></xref> and are returned using
<xref href="ArcGIS.Core.Data.RelationshipClass.GetRowsRelatedToOriginRows(System.Collections.Generic.IEnumerable%7bSystem.Int64%7d)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.RelationshipClass.GetRowsRelatedToDestinationRows(System.Collections.Generic.IEnumerable%7bSystem.Int64%7d)" data-throw-if-not-resolved="false"></xref>.
<xref href="ArcGIS.Core.Data.AttributedRelationship" data-throw-if-not-resolved="false"></xref></p>


## Members

### GetDestinationRow()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Relationship.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> from the destination table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Row GetDestinationRow()
```
### GetOriginRow()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Relationship.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> from the origin table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Row GetOriginRow()
```


