# VersionManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">This class provides basic functionality to manage versioning on behalf of an enterprise or web <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class VersionManager : CoreObjectsBase, IDisposable
```


## Members

### CreateHistoricalVersion(HistoricalVersionDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public HistoricalVersion CreateHistoricalVersion(HistoricalVersionDescription historicalVersionDescription)
```
### CreateVersion(VersionDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Version CreateVersion(VersionDescription versionDescription)
```
### CreateVersion(VersionDescription, Version)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Creates a new <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> as a child of <code class="paramref">parent</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Version CreateVersion(VersionDescription versionDescription, Version parent)
```
### GetCurrentHistoricalVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets the currently active <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public HistoricalVersion GetCurrentHistoricalVersion()
```
### GetCurrentVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets the currently active <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Version GetCurrentVersion()
```
### GetCurrentVersionBaseType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets whether the <code>VersionManager</code> belongs to a Geodatabase that is connected to a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public VersionBaseType GetCurrentVersionBaseType()
```
### GetDefaultVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets the default <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Version GetDefaultVersion()
```
### GetHistoricalVersion(DateTime)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref> object with the specified <code class="paramref">moment</code>.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public HistoricalVersion GetHistoricalVersion(DateTime moment)
```
### GetHistoricalVersion(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref> object with the specified <code class="paramref">markerName</code>.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public HistoricalVersion GetHistoricalVersion(string markerName)
```
### GetHistoricalVersions()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of all the available <xref href="ArcGIS.Core.Data.HistoricalVersion" data-throw-if-not-resolved="false"></xref> in a given enterprise geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<HistoricalVersion> GetHistoricalVersions()
```
### GetVersion(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> object with the specified <code class="paramref">name</code>.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Version GetVersion(string name)
```
### GetVersionDefinitions()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a list of descriptions of all the available <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref>s in a given enterprise geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<VersionDefinition> GetVersionDefinitions()
```
### GetVersionNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of the names of all available <xref href="ArcGIS.Core.Data.Version" data-throw-if-not-resolved="false"></xref> in a given enterprise geodatabase.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetVersionNames()
```
### GetVersioningType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.VersionManager.yml" sourcestartlinenumber="1">Gets a value indicating whether the <xref href="ArcGIS.Core.Data.Geodatabase" data-throw-if-not-resolved="false"></xref> supports traditional or branch versioning.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public VersionType GetVersioningType()
```


