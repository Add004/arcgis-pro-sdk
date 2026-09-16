# ConflictCategory

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">Specifies the category of conflict in a row of a versioned feature class.</p>


## Object Signature

```csharp
public enum ConflictCategory
```


## Members

### Attribute

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">The conflict was generated from the attribute level.</p>


```csharp
Attribute = 2
```
### Container

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">The conflict was generated from a container.</p>


```csharp
Container = 4
```
### Contents

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">The conflict was generated from contents.</p>


```csharp
Contents = 5
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">There is no category for this conflict.</p>


```csharp
None = 0
```
### Relational

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">The conflict was generated from a relation.</p>


```csharp
Relational = 3
```
### Row

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.ConflictCategory.yml" sourcestartlinenumber="1">The conflict was generated from the row level.</p>


```csharp
Row = 1
```


