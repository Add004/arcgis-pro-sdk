# JoinDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Join" data-throw-if-not-resolved="false"></xref> object.</p>


## Object Signature

```csharp
public sealed class JoinDescription
```


## Members

### JoinDescription(RelationshipClass)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>JoinDescription</code> class.</p>


```csharp
public JoinDescription(RelationshipClass relationshipClass)
```
### ErrorOnFailureToProcessJoinOnServerSide

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether an exception should be raised if the join operation cannot be processed on the server side.</p>


```csharp
public bool ErrorOnFailureToProcessJoinOnServerSide { get; set; }
```
### JoinDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the join proceeds from the left table to the right table (Forward) or from the right table to the left table (Backward).
The default value is <xref href="ArcGIS.Core.Data.JoinDirection.Forward" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public JoinDirection JoinDirection { get; set; }
```
### JoinType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the join is an inner join or a left outer join.
The default value is <xref href="ArcGIS.Core.Data.JoinType.InnerJoin" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public JoinType JoinType { get; set; }
```
### QueryFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.QueryFilter" data-throw-if-not-resolved="false"></xref> to be used if the result of the join has to be filtered based on a query.</p>


```csharp
public QueryFilter QueryFilter { get; set; }
```
### RelationshipClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> that was passed into the <code>JoinDescription</code> constructor.</p>


```csharp
public RelationshipClass RelationshipClass { get; }
```
### Selection

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref> to be used in creating the join.</p>


```csharp
public Selection Selection { get; set; }
```
### TargetFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.JoinDescription.yml" sourcestartlinenumber="1">Gets or sets the fields from the left table which have to be included during the join operation.</p>


```csharp
public IReadOnlyList<Field> TargetFields { get; set; }
```


