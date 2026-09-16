# PostOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.PostOptions.yml" sourcestartlinenumber="1">Represents a mechanism to post a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class PostOptions
```


## Members

### PostOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PostOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>PostOptions</code> class for a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to post
to the <b>default</b> version.</p>


```csharp
public PostOptions()
```
### PostOptions(Version)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PostOptions.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>PostOptions</code> class for a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to post
to the <code class="paramref">targetVersion</code>.</p>


```csharp
public PostOptions(Version targetVersion)
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PostOptions.yml" sourcestartlinenumber="1">Gets or sets whether or not Post should run synchronously.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```
### TargetVersion

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PostOptions.yml" sourcestartlinenumber="1">Gets the target <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> to be posted against.  If <b>null</b>, the target is the <b>default</b> version.</p>


```csharp
public Version TargetVersion { get; }
```


