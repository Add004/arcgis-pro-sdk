# PluginDatasourceConnectionPath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath.yml" sourcestartlinenumber="1">Represents the identification of a data source made available to ArcGIS Pro via a plug-in data source add-in.</p>


## Object Signature

```csharp
public sealed class PluginDatasourceConnectionPath : Connector
```


## Members

### PluginDatasourceConnectionPath(string, Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PluginDatasourceConnectionPath(string pluginIdentifier, Uri datasourcePath)
```
### DatasourcePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath.yml" sourcestartlinenumber="1">The connection string specifying a third-party data source.</p>


```csharp
public Uri DatasourcePath { get; }
```
### PluginIdentifier

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath.yml" sourcestartlinenumber="1">The identification string of a plug-in data source add-in.</p>


```csharp
public string PluginIdentifier { get; }
```


