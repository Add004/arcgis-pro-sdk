# SchemaBuilder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">This class is used to perform all DDL (data definition language) tasks in the Pro SDK.</p>


## Object Signature

```csharp
public sealed class SchemaBuilder
```


## Members

### SchemaBuilder(Geodatabase)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a schema builder object based on the input <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SchemaBuilder(Geodatabase geodatabase)
```
### SchemaBuilder(KnowledgeGraph)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a schema builder object based on the input <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SchemaBuilder(KnowledgeGraph knowledgeGraph)
```
### AddFeatureClass(FeatureDatasetDescription, AnnotationFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Add operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddFeatureClass(FeatureDatasetDescription featureDatasetDescription, AnnotationFeatureClassDescription annotationFeatureClassDescription)
```
### AddFeatureClass(FeatureDatasetDescription, DimensionFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Add operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddFeatureClass(FeatureDatasetDescription featureDatasetDescription, DimensionFeatureClassDescription dimensionFeatureClassDescription)
```
### AddFeatureClass(FeatureDatasetDescription, FeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Add operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.FeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddFeatureClass(FeatureDatasetDescription featureDatasetDescription, FeatureClassDescription featureClassDescription)
```
### AddRelationshipClass(FeatureDatasetDescription, AttributedRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Add operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddRelationshipClass(FeatureDatasetDescription featureDatasetDescription, AttributedRelationshipClassDescription attributedRelationshipClassDescription)
```
### AddRelationshipClass(FeatureDatasetDescription, RelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Add operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void AddRelationshipClass(FeatureDatasetDescription featureDatasetDescription, RelationshipClassDescription relationshipClassDescription)
```
### Build()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Performs all enqueued operations.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool Build()
```
### Create(AnnotationFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AnnotationFeatureClassToken Create(AnnotationFeatureClassDescription annotationFeatureClassDescription)
```
### Create(AttributedRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributedRelationshipClassToken Create(AttributedRelationshipClassDescription attributedRelationshipClassDescription)
```
### Create(CodedValueDomainDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.CodedValueDomainDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CodedValueDomainToken Create(CodedValueDomainDescription codedValueDomainDescription)
```
### Create(DimensionFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionFeatureClassToken Create(DimensionFeatureClassDescription dimensionFeatureClassDescription)
```
### Create(FeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClassToken Create(FeatureClassDescription featureClassDescription)
```
### Create(FeatureDatasetDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureDatasetToken Create(FeatureDatasetDescription featureDatasetDescription)
```
### Create(FeatureDatasetDescription, AnnotationFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AnnotationFeatureClassToken Create(FeatureDatasetDescription featureDatasetDescription, AnnotationFeatureClassDescription annotationFeatureClassDescription)
```
### Create(FeatureDatasetDescription, AttributedRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributedRelationshipClassToken Create(FeatureDatasetDescription featureDatasetDescription, AttributedRelationshipClassDescription attributedRelationshipClassDescription)
```
### Create(FeatureDatasetDescription, DimensionFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionFeatureClassToken Create(FeatureDatasetDescription featureDatasetDescription, DimensionFeatureClassDescription dimensionFeatureClassDescription)
```
### Create(FeatureDatasetDescription, FeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FeatureClassToken Create(FeatureDatasetDescription featureDatasetDescription, FeatureClassDescription featureClassDescription)
```
### Create(FeatureDatasetDescription, RelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipClassToken Create(FeatureDatasetDescription featureDatasetDescription, RelationshipClassDescription relationshipClassDescription)
```
### Create(IndexDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.IndexDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Create(IndexDescription indexDescription)
```
### Create(KnowledgeGraphTypeDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphTypeToken Create(KnowledgeGraphTypeDescription namedObjectTypeDescription)
```
### Create(RangeDomainDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.RangeDomainDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RangeDomainToken Create(RangeDomainDescription rangeDomainDescription)
```
### Create(RelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public RelationshipClassToken Create(RelationshipClassDescription relationshipClassDescription)
```
### Create(TableDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the create operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.TableDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TableToken Create(TableDescription tableDescription)
```
### CreateFileKnowledgeGraph(KnowledgeGraphConnectionProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a new file <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref> at the specified path.</p>


```csharp
public static KnowledgeGraph CreateFileKnowledgeGraph(KnowledgeGraphConnectionProperties kgConnectionPath)
```
### CreateGeodatabase(FileGeodatabaseConnectionPath)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a new file <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> at the specified path.</p>


```csharp
public static Geodatabase CreateGeodatabase(FileGeodatabaseConnectionPath fileGeodatabaseConnectionPath)
```
### CreateGeodatabase(MemoryConnectionProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a new memory <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> with the specified name.</p>


```csharp
public static Geodatabase CreateGeodatabase(MemoryConnectionProperties memoryConnectionProperties)
```
### CreateGeodatabase(MobileGeodatabaseConnectionPath)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Creates a new mobile <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> at the specified path</p>


```csharp
public static Geodatabase CreateGeodatabase(MobileGeodatabaseConnectionPath mobileGeodatabaseConnectionPath)
```
### Delete(Description)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the delete operation on the object with the name referred to by the <xref href="ArcGIS.Core.Data.DDL.Description" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Delete(Description description)
```
### DeleteGeodatabase(FileGeodatabaseConnectionPath)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Deletes the file <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> at the specified path.</p>


```csharp
public static void DeleteGeodatabase(FileGeodatabaseConnectionPath fileGeodatabaseConnectionPath)
```
### DeleteGeodatabase(MemoryConnectionProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Deletes the memory <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> with the specified name.</p>


```csharp
public static void DeleteGeodatabase(MemoryConnectionProperties memoryConnectionProperties)
```
### DeleteGeodatabase(MobileGeodatabaseConnectionPath)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Deletes the mobile <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> at the specified path</p>


```csharp
public static void DeleteGeodatabase(MobileGeodatabaseConnectionPath mobileGeodatabaseConnectionPath)
```
### ErrorMessages

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Gets information about failed operations.</p>


```csharp
public IReadOnlyList<string> ErrorMessages { get; }
```
### Modify(AnnotationFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(AnnotationFeatureClassDescription annotationFeatureClassDescription)
```
### Modify(AttributedRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(AttributedRelationshipClassDescription attributedRelationshipClassDescription)
```
### Modify(CodedValueDomainDescription, SortBy, SortOrder)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.CodedValueDomainDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(CodedValueDomainDescription codedValueDomainDescription, SortBy sortBy, SortOrder sortOrder)
```
### Modify(DimensionFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(DimensionFeatureClassDescription dimensionFeatureClassDescription)
```
### Modify(DomainDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.DomainDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(DomainDescription domainDescription)
```
### Modify(FeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(FeatureClassDescription featureClassDescription)
```
### Modify(KnowledgeGraphTypeDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by
the <xref href="ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphTypeDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(KnowledgeGraphTypeDescription kgTypeDescription)
```
### Modify(RelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(RelationshipClassDescription relationshipClassDescription)
```
### Modify(TableDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.TableDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(TableDescription tableDescription)
```
### Modify(TableDescription, string, FieldDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the modify operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.TableDescription" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Modify(TableDescription tableDescription, string fieldName, FieldDescription fieldDescription)
```
### RemoveFeatureClass(FeatureDatasetDescription, AnnotationFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Remove operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void RemoveFeatureClass(FeatureDatasetDescription featureDatasetDescription, AnnotationFeatureClassDescription annotationFeatureClassDescription)
```
### RemoveFeatureClass(FeatureDatasetDescription, DimensionFeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Remove operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void RemoveFeatureClass(FeatureDatasetDescription featureDatasetDescription, DimensionFeatureClassDescription dimensionFeatureClassDescription)
```
### RemoveFeatureClass(FeatureDatasetDescription, FeatureClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Remove operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.FeatureClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void RemoveFeatureClass(FeatureDatasetDescription featureDatasetDescription, FeatureClassDescription featureClassDescription)
```
### RemoveRelationshipClass(FeatureDatasetDescription, AttributedRelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Remove operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.AttributedRelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void RemoveRelationshipClass(FeatureDatasetDescription featureDatasetDescription, AttributedRelationshipClassDescription attributedRelationshipClassDescription)
```
### RemoveRelationshipClass(FeatureDatasetDescription, RelationshipClassDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the Remove operation on the object referred to by the <xref href="ArcGIS.Core.Data.DDL.FeatureDatasetDescription" data-throw-if-not-resolved="false"></xref> and the <xref href="ArcGIS.Core.Data.DDL.RelationshipClassDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public void RemoveRelationshipClass(FeatureDatasetDescription featureDatasetDescription, RelationshipClassDescription relationshipClassDescription)
```
### Rename(Description, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.SchemaBuilder.yml" sourcestartlinenumber="1">Enqueue the rename operation on the object with the name referred to by the <xref href="ArcGIS.Core.Data.DDL.Description" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Token Rename(Description description, string newName)
```


