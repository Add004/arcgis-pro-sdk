# Definition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Definition.yml" sourcestartlinenumber="1">Represents a definition of a geodatabase <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class Definition : CoreObjectsBase, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Definition.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> of the definition.</p>


```csharp
public abstract DatasetType DatasetType { get; }
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Definition.yml" sourcestartlinenumber="1">Gets the name of the definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```


