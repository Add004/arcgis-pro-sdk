# Join

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Represents a mechanism to join tables from the same or different <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class Join : CoreObjectsBase, IDisposable
```


## Members

### Join(JoinDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>Join</code> class, which represents the join of a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> with another <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>
from the same or different <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Join(JoinDescription joinDescription)
```
### FindFieldIgnoreQualification(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the zero-based index of the first field in the joined table whose name matches <code class="paramref">fieldName</code>.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public int FindFieldIgnoreQualification(string fieldName)
```
### GetDestinationTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> which corresponds to the <code>destination table</code> used to create the join.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Table GetDestinationTable()
```
### GetJoinedTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> representing the join. This provides access to perform operations like <code>Search</code> and <code>Select</code> on the joined data.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Table GetJoinedTable()
```
### GetOriginTable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> which corresponds to the <code>origin table</code> used to create the join.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Table GetOriginTable()
```
### GetRelationshipClass()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> which corresponds to the relationship class used to create the join.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public RelationshipClass GetRelationshipClass()
```
### GetTableAssociatedWithField(Field)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the origin or destination <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> that has a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> whose name matches that of <code class="paramref">field</code>.
This method must be called on the MCT.  Use QueuedTask.Run.</p>


```csharp
public Table GetTableAssociatedWithField(Field field)
```
### IsJoinPerformedOnClientSide

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets a value indicating whether the joined table was created by querying the tables separately and joined on the client side or the join was performed entirely on the server side.</p>


```csharp
public bool IsJoinPerformedOnClientSide { get; }
```
### JoinType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Join.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.JoinType" data-throw-if-not-resolved="false"></xref> used to create this object via <xref href="ArcGIS.Core.Data.Join.%23ctor(ArcGIS.Core.Data.JoinDescription)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public JoinType JoinType { get; }
```


