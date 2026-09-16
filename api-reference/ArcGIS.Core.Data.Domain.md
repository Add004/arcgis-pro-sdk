# Domain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Represents a domain from a geodatabase.</p>


## Object Signature

```csharp
public abstract class Domain : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">A domain maintains the information about a specific domain in the geodatabase, including its name, description and the FieldType it can be assigned to.</p>


## Members

### GetDescription()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Gets the description of the domain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDescription()
```
### GetFieldType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> of the domain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public FieldType GetFieldType()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Gets the name of the domain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### MergePolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.MergePolicy" data-throw-if-not-resolved="false"></xref> of the domain.</p>


```csharp
public MergePolicy MergePolicy { get; }
```
### SplitPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Domain.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.SplitPolicy" data-throw-if-not-resolved="false"></xref> of the domain.</p>


```csharp
public SplitPolicy SplitPolicy { get; }
```


