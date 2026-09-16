# AttributedRelationship

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Represents a pair of related rows (or features) from a geodatabase with extra information stored as a row in an intermediate table.</p>


## Object Signature

```csharp
public sealed class AttributedRelationship : Relationship, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">An <xref href="ArcGIS.Core.Data.AttributedRelationship" data-throw-if-not-resolved="false"></xref> represents a relationship between rows and/or features where the tables or
feature classes must participate in an <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>. AttributedRelationships are created
using either <xref href="ArcGIS.Core.Data.AttributedRelationshipClass.CreateRelationship(ArcGIS.Core.Data.Row%2cArcGIS.Core.Data.Row)" data-throw-if-not-resolved="false"></xref>
(if the AttributedRelationshipClass does <b>not</b> have user-defined attributes other than those created by the system) or
<xref href="ArcGIS.Core.Data.AttributedRelationshipClass.CreateRelationship(ArcGIS.Core.Data.Row%2cArcGIS.Core.Data.Row%2cArcGIS.Core.Data.RowBuffer)" data-throw-if-not-resolved="false"></xref>
(if the AttributedRelationshipClass does have user-defined attributes beyond those created by the system).  They are returned
using <xref href="ArcGIS.Core.Data.AttributedRelationshipClass.GetRelationshipsForOriginRows(System.Collections.Generic.IEnumerable%7bSystem.Int64%7d)" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Core.Data.AttributedRelationshipClass.GetRelationshipsForDestinationRows(System.Collections.Generic.IEnumerable%7bSystem.Int64%7d)" data-throw-if-not-resolved="false"></xref>.
<xref href="ArcGIS.Core.Data.Relationship" data-throw-if-not-resolved="false"></xref></p>


## Members

### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing the fields of the attributed relationship, which is a row in
the intermediate table of an attributed relationship class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Gets the object ID of the row.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public long GetObjectID()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its attribute name or alias name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### Store()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributedRelationship.yml" sourcestartlinenumber="1">Stores the row in the intermediate table of an AttributedRelationshipClass.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Store()
```


