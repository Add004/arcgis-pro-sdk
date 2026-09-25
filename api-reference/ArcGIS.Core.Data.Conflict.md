# Conflict

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">Represents a single conflict between two <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> instances.</p>


## Object Signature

```csharp
public sealed class Conflict
```


## Members

### AncestorVersionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The values of the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in the common ancestor version.</p>


```csharp
public IReadOnlyList<FieldValue> AncestorVersionValues { get; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The category of conflict which occurred.</p>


```csharp
public ConflictCategory Category { get; }
```
### ChildVersionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The values of the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in the current version or an empty list if the feature has been deleted.</p>


```csharp
public IReadOnlyList<FieldValue> ChildVersionValues { get; }
```
### ConflictType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The type of conflict which occurred.</p>


```csharp
public ConflictType ConflictType { get; }
```
### DatasetName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The name of the <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> in which the conflict occurred.</p>


```csharp
public string DatasetName { get; }
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The GlobalID of the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> where the conflict occurred.</p>


```csharp
public Guid GlobalID { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The ObjectID of the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> where the conflict occurred.</p>


```csharp
public long ObjectID { get; }
```
### ParentVersionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Conflict.yml" sourcestartlinenumber="1">The values of the <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in the target version or an empty list if the feature has been deleted.</p>


```csharp
public IReadOnlyList<FieldValue> ParentVersionValues { get; }
```


