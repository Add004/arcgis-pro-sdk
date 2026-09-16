# Geodatabase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Represents an ArcGIS geodatabase.</p>


## Object Signature

```csharp
public sealed class Geodatabase : Datastore, IDisposable
```


## Members

### Geodatabase(ArcGISServerConnectionFile)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a web geodatabase given a <code class="paramref">connectionFile</code> to a valid service connection.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(ArcGISServerConnectionFile connectionFile)
```
### Geodatabase(DatabaseConnectionFile)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens an enterprise geodatabase with the specified connection file.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(DatabaseConnectionFile databaseConnectionFile)
```
### Geodatabase(DatabaseConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens an enterprise geodatabase with the specified connection properties.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(DatabaseConnectionProperties databaseConnectionProperties)
```
### Geodatabase(FileGeodatabaseConnectionPath)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a file geodatabase with the specified <code class="paramref">connectionPath</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(FileGeodatabaseConnectionPath connectionPath)
```
### Geodatabase(MemoryConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a memory geodatabase with the specified <code class="paramref">memoryConnectionProperties</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(MemoryConnectionProperties memoryConnectionProperties)
```
### Geodatabase(MobileGeodatabaseConnectionPath)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a mobile geodatabase with the specified <code class="paramref">connectionPath</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(MobileGeodatabaseConnectionPath connectionPath)
```
### Geodatabase(ServiceConnectionProperties)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a web geodatabase given a <code class="paramref">serviceConnectionProperties</code> to a valid feature service location.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geodatabase(ServiceConnectionProperties serviceConnectionProperties)
```
### ApplyEdits(Action)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Executes the <code class="paramref">action</code> delegate as a single transaction.
The transaction either completes successfully or is aborted and rolled back.</p>


```csharp
public void ApplyEdits(Action action)
```
### ApplyEdits(Action, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Executes the <code class="paramref">action</code> delegate as a single transaction in a given versioned edit session mode.
The transaction either completes successfully or is aborted and rolled back.</p>


```csharp
public void ApplyEdits(Action action, bool isVersionedEditSession)
```
### Evaluate(QueryDef, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Evaluates the query and return a <xref href="ArcGIS.Core.Data.RowCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RowCursor Evaluate(QueryDef queryDef, bool useRecyclingCursor = true)
```
### GetAttributeRuleManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.AttributeRuleManager" data-throw-if-not-resolved="false"></xref> associated with this geodatabase if it supports attribute rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributeRuleManager GetAttributeRuleManager()
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T GetDefinition<T>(string name) where T : Definition
```
### GetDefinitions&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of specific <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instances
associated with each dataset of type <code class="typeparamref">T</code> in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<T> GetDefinitions<T>() where T : Definition
```
### GetDomains()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets all the <xref href="ArcGIS.Core.Data.Domain" data-throw-if-not-resolved="false"></xref> in this geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Domain> GetDomains()
```
### GetGeodatabaseType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.GeodatabaseType" data-throw-if-not-resolved="false"></xref> associated with the currently opened geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GeodatabaseType GetGeodatabaseType()
```
### GetRelatedDefinitions(Definition, DefinitionRelationshipType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> instances where each one is
related to <code class="paramref">definition</code> by satisfying the <code class="paramref">relationshipType</code> constraint in the geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Definition> GetRelatedDefinitions(Definition definition, DefinitionRelationshipType relationshipType)
```
### GetVersionManager()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.VersionManager" data-throw-if-not-resolved="false"></xref> associated with this geodatabase if it supports versioning.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VersionManager GetVersionManager()
```
### IsAttributeRuleSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a value indicating whether this geodatabase supports attribute rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsAttributeRuleSupported()
```
### IsVersioningSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a value indicating whether this geodatabase supports versioning.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsVersioningSupported()
```
### OpenDataset&lt;T&gt;(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a specific <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> instance associated with <code class="paramref">name</code> of type <code class="typeparamref">T</code>
in the geodatabase. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public T OpenDataset<T>(string name) where T : Dataset
```
### OpenQueryTable(QueryTableDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Opens a <code>query table</code> based on the <code class="paramref">queryTableDescription</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table OpenQueryTable(QueryTableDescription queryTableDescription)
```
### OpenRelationshipClasses(Table, Table)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of specific <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref> instances
associated with the <code class="paramref">originTable</code> and the <code class="paramref">destinationTable</code> where <code class="paramref">originTable</code> is the origin table/feature class
and <code class="paramref">destinationTable</code> is the destination table/feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<RelationshipClass> OpenRelationshipClasses(Table originTable, Table destinationTable)
```
### OpenRelationshipClasses(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Geodatabase.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of specific <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref> instances
associated with the <code class="paramref">originClass</code> and the <code class="paramref">destinationClass</code> where <code class="paramref">originClass</code> is the origin table/feature class
and <code class="paramref">destinationClass</code> is the destination table/feature class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<RelationshipClass> OpenRelationshipClasses(string originClass, string destinationClass)
```


