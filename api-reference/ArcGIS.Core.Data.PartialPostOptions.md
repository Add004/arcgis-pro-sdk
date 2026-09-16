# PartialPostOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.PartialPostOptions.yml" sourcestartlinenumber="1">Represents a mechanism to partial post a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class PartialPostOptions
```


## Members

### PartialPostOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PartialPostOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>PartialPostOptions</code> class for a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to partial post to the default version.</p>


```csharp
public PartialPostOptions()
```
### ConflictDetectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PartialPostOptions.yml" sourcestartlinenumber="1">Gets or sets the conflict detection type.</p>


```csharp
public ConflictDetectionType ConflictDetectionType { get; set; }
```
### Selections

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PartialPostOptions.yml" sourcestartlinenumber="1">Gets or sets a list of <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref> objects based on <xref href="ArcGIS.Core.Data.SelectionType.ObjectID" data-throw-if-not-resolved="false"></xref> to be posted to
the <b>default</b> version.</p>


```csharp
public IReadOnlyList<Selection> Selections { get; set; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PartialPostOptions.yml" sourcestartlinenumber="1">Gets or sets whether or not Post should run synchronously.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```


