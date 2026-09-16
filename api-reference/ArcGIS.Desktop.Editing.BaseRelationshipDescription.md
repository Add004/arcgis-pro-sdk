# BaseRelationshipDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.BaseRelationshipDescription.yml" sourcestartlinenumber="1">Base class for representing a relationship between two rows.  See <xref href="ArcGIS.Desktop.Editing.RelationshipDescription" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.KnowledgeGraphRelationshipDescription" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class BaseRelationshipDescription
```


## Members

### Attributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.BaseRelationshipDescription.yml" sourcestartlinenumber="1">Gets the attributes to assign to the new row in the relationship table.</p>


```csharp
public IReadOnlyDictionary<string, object> Attributes { get; }
```
### DestinationRow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.BaseRelationshipDescription.yml" sourcestartlinenumber="1">Gets the RowHandle of the row in the destination table.</p>


```csharp
public RowHandle DestinationRow { get; }
```
### OriginRow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.BaseRelationshipDescription.yml" sourcestartlinenumber="1">Gets the RowHandle of the row in the origin table.</p>


```csharp
public RowHandle OriginRow { get; }
```


