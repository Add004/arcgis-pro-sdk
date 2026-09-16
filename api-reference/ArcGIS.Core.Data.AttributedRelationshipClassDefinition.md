# AttributedRelationshipClassDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of an <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AttributedRelationshipClassDefinition : RelationshipClassDefinition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the dataset type.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetDestinationForeignKeyField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the destination foreign key field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDestinationForeignKeyField()
```
### GetDestinationKeyField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the destination primary key field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDestinationKeyField()
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the fields in the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>'s intermediate table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetObjectIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationshipClassDefinition.yml" sourcestartlinenumber="1">Gets the name of the ObjectID field in the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>'s intermediate table.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetObjectIDField()
```


