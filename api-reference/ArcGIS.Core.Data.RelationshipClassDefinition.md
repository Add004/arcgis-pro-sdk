# RelationshipClassDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class RelationshipClassDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the dataset type.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### GetAliasName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the alias name of the definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAliasName()
```
### GetBackwardPathLabel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the label that displays when navigating from the destination to the origin.</p>


```csharp
public string GetBackwardPathLabel()
```
### GetCardinality()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the valid cardinality of the relationship.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipCardinality GetCardinality()
```
### GetDestinationClass()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the destination class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDestinationClass()
```
### GetForwardPathLabel()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the label that displays when navigating from the origin to the destination.</p>


```csharp
public string GetForwardPathLabel()
```
### GetMessageDirection()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the message notification direction.</p>


```csharp
public RelationshipMessageDirection GetMessageDirection()
```
### GetOriginClass()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the origin class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetOriginClass()
```
### GetOriginForeignKeyField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the origin foreign key field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetOriginForeignKeyField()
```
### GetOriginKeyField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the origin (primary) key field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetOriginKeyField()
```
### GetRelationshipRules()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the list of relationship rules in the relationship class.</p>


```csharp
public IReadOnlyList<RelationshipRule> GetRelationshipRules()
```
### GetRelationshipSplitPolicy()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the split policy of the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipSplitPolicy GetRelationshipSplitPolicy()
```
### IsAttachmentRelationship()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets a value which indicates if the relationship is used to enable attachment support for a table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsAttachmentRelationship()
```
### IsComposite()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.RelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether the lifetime of the destination rows are dependent on the lifetime of the origin rows.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsComposite()
```


