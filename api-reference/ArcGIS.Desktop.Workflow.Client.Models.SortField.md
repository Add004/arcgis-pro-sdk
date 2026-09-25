# SortField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


## Object Signature

```csharp
public record SortField : IEquatable<SortField>
```


## Members

### SortField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public SortField()
```
### SortField(SortField)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
protected SortField(SortField original)
```
### EqualityContract

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
protected virtual Type EqualityContract { get; }
```
### Equals(SortField?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public virtual bool Equals(SortField? other)
```
### Equals(object?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public override bool Equals(object? obj)
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Name of the field to sort by</p>


```csharp
public string FieldName { get; set; }
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public override int GetHashCode()
```
### PrintMembers(StringBuilder)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
protected virtual bool PrintMembers(StringBuilder builder)
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort field by ascending or descending order</p>


```csharp
public SortOrder SortOrder { get; set; }
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public override string ToString()
```
### operator ==(SortField?, SortField?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public static bool operator ==(SortField? left, SortField? right)
```
### operator !=(SortField?, SortField?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.SortField.yml" sourcestartlinenumber="1">Sort fields for a search</p>


```csharp
public static bool operator !=(SortField? left, SortField? right)
```


