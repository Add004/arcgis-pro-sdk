# PluginDatasourceTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of a concrete class that implements this abstraction acts as a conduit between
    a third-party data source and ArcGIS Pro via the deployment of a plug-in data source add-in.
    </p>
<p>
    Currently, the framework only supports <xref href="ArcGIS.Core.Data.DatasetType.Table" data-throw-if-not-resolved="false"></xref>s and 
    <xref href="ArcGIS.Core.Data.DatasetType.FeatureClass" data-throw-if-not-resolved="false"></xref>s in a read-only manner.
    </p>


## Object Signature

```csharp
public abstract class PluginDatasourceTemplate
```


## Members

### PluginDatasourceTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected PluginDatasourceTemplate()
```
### CanOpen(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets a value indicating whether the data source associated with <code class="paramref">connectionPath</code> can be opened
by this concrete implementation.</p>


```csharp
public virtual bool CanOpen(Uri connectionPath)
```
### Close()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Formally closes the Plugin Datasource.  This operation is the opposite of <xref href="ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.Open(System.Uri)" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract void Close()
```
### GetDatasetDescription(DatasetType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets a string description for <code class="paramref">datasetType</code>.</p>


```csharp
public virtual string GetDatasetDescription(DatasetType datasetType)
```
### GetDatasourceDescription(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets a string description for the plug-in data source depending on <code class="paramref">inPluralForm</code>.</p>


```csharp
public virtual string GetDatasourceDescription(bool inPluralForm)
```
### GetTableNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets the name of all the tables and feature classes that exist in the currently opened plug-in data source.</p>


```csharp
public abstract IReadOnlyList<string> GetTableNames()
```
### IsQueryLanguageSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets a value indicating whether the underlying data source supports a query language (e.g., SQL).</p>


```csharp
public virtual bool IsQueryLanguageSupported()
```
### Open(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Formally opens the Plugin Datasource in order for the new data format to be integrated into ArcGIS Pro.</p>


```csharp
public abstract void Open(Uri connectionPath)
```
### OpenTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceTemplate.yml" sourcestartlinenumber="1">Gets an instance of concrete class that implements the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate" data-throw-if-not-resolved="false"></xref>
abstraction associated with <code class="paramref">name</code> in the plug-in data source.</p>


```csharp
public abstract PluginTableTemplate OpenTable(string name)
```


