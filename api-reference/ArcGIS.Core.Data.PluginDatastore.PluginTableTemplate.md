# PluginTableTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of concrete class that implements this abstraction acts as a conduit between
    a data structure in a third-party data source and a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> (or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>) in ArcGIS Pro.
    </p>
<p>
    A plug-in table does not necessarily correspond to a database table on the back end. It can be any data structure or format, but it <i>presented</i> to ArcGIS as a table.
    </p>
<p>
    If the list of <xref href="ArcGIS.Core.Data.PluginDatastore.PluginField" data-throw-if-not-resolved="false"></xref>s returned by <xref href="ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.GetFields" data-throw-if-not-resolved="false"></xref> has a field whose type is <xref href="ArcGIS.Core.Data.FieldType.Geometry" data-throw-if-not-resolved="false"></xref>, 
    then this concrete implementation is considered a feature class; otherwise, a table.
    </p>


## Object Signature

```csharp
public abstract class PluginTableTemplate
```


## Members

### PluginTableTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected PluginTableTemplate()
```
### GetExtent()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> of this plug-in table if it supports spatial functionality.</p>


```csharp
public virtual Envelope GetExtent()
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets all of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginField" data-throw-if-not-resolved="false"></xref>s for this currently opened plug-in table or feature class.</p>


```csharp
public abstract IReadOnlyList<PluginField> GetFields()
```
### GetLastModifiedTime()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets the last modified timestamp of the table.</p>


```csharp
public virtual DateTime GetLastModifiedTime()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets the name of this currently opened plug-in table or feature class.</p>


```csharp
public abstract string GetName()
```
### GetNativeRowCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets the count of how many rows are currently in this plug-in table or feature class.</p>


```csharp
public virtual long GetNativeRowCount()
```
### GetShapeType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.GeometryType" data-throw-if-not-resolved="false"></xref> of this plug-in table if it supports spatial functionality.</p>


```csharp
public virtual GeometryType GetShapeType()
```
### IsNativeRowCountSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Gets a value indicating whether the plug-in table or feature class supports row count natively.</p>


```csharp
public virtual bool IsNativeRowCountSupported()
```
### Search(QueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Performs a non-spatial search on this plug-in table that satisfies the criteria set in the <code class="paramref">queryFilter</code>.</p>


```csharp
public abstract PluginCursorTemplate Search(QueryFilter queryFilter)
```
### Search(SpatialQueryFilter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.yml" sourcestartlinenumber="1">Performs a spatial search on this plug-in feature class that satisfies the criteria set in the <code class="paramref">spatialQueryFilter</code>.</p>


```csharp
public abstract PluginCursorTemplate Search(SpatialQueryFilter spatialQueryFilter)
```


