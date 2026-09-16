# RelationshipDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RelationshipDescription.yml" sourcestartlinenumber="1">Represents a relationship between two rows.</p>


## Object Signature

```csharp
public sealed class RelationshipDescription : BaseRelationshipDescription
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.RelationshipDescription.yml" sourcestartlinenumber="1">A RelationshipDescription is used to create and delete a relationship between two rows defined by a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.
Once defined, use EditOperation.Create to create the relationship and EditOperation.Delete to remove the relationship.</p>


## Members

### RelationshipDescription(RelationshipClass, RowHandle, RowHandle, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RelationshipDescription.yml" sourcestartlinenumber="1">Creates a new instance of the RelationshipDescription class.</p>


```csharp
public RelationshipDescription(RelationshipClass relationshipClass, RowHandle origin, RowHandle destination, IReadOnlyDictionary<string, object> attributes = null)
```
### RelationshipClass

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RelationshipDescription.yml" sourcestartlinenumber="1">Gets the RelationshipClass representing an association between two tables in a geodatabase.</p>


```csharp
public RelationshipClass RelationshipClass { get; }
```


