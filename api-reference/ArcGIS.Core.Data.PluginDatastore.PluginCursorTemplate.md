# PluginCursorTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of concrete class that implements this abstraction acts as a conduit between
    a cursor traversing a data structure in a third-party data source and a <xref href="ArcGIS.Core.Data.RowCursor" data-throw-if-not-resolved="false"></xref> object in ArcGIS Pro.
    </p>


## Object Signature

```csharp
public abstract class PluginCursorTemplate
```


## Members

### PluginCursorTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
protected PluginCursorTemplate()
```
### GetCurrentRow()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.PluginDatastore.PluginRow" data-throw-if-not-resolved="false"></xref> in this concrete instance of <xref href="ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract PluginRow GetCurrentRow()
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.PluginDatastore.PluginRow" data-throw-if-not-resolved="false"></xref> in this concrete instance of <xref href="ArcGIS.Core.Data.PluginDatastore.PluginCursorTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public abstract bool MoveNext()
```


