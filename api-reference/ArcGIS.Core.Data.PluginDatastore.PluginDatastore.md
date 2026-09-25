# PluginDatastore

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Represents a plug-in data store that makes a third-party data format accessible to ArcGIS Pro, albeit in a read-only manner.</p>


## Object Signature

```csharp
public sealed class PluginDatastore : Datastore, IDisposable
```


## Members

### PluginDatastore(PluginDatasourceConnectionPath)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Opens a read-only plug-in data store that makes a third-party data format accessible to ArcGIS Pro.</p>


```csharp
public PluginDatastore(PluginDatasourceConnectionPath connector)
```
### GetConnector()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Connector" data-throw-if-not-resolved="false"></xref> associated with the currently opened plug-in data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override Connector GetConnector()
```
### GetDefinition(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.TableDefinition" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClassDefinition" data-throw-if-not-resolved="false"></xref>
(if the table returned by <xref href="ArcGIS.Core.Data.PluginDatastore.PluginDatastore.OpenTable(System.String)" data-throw-if-not-resolved="false"></xref> can be cast to <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>) associated
with <code class="paramref">name</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public TableDefinition GetDefinition(string name)
```
### GetTableNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Gets the name of all the tables that exist in the currently opened plug-in data store.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetTableNames()
```
### OpenTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> (if it is spatially enabled) associated
with <code class="paramref">name</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table OpenTable(string name)
```


