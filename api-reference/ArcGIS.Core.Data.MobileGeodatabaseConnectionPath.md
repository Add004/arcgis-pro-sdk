# MobileGeodatabaseConnectionPath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.MobileGeodatabaseConnectionPath.yml" sourcestartlinenumber="1">Represents the physical path to a mobile geodatabase that ends with the <i>.geodatabase</i> extension.</p>


## Object Signature

```csharp
public sealed class MobileGeodatabaseConnectionPath : Connector
```


## Members

### MobileGeodatabaseConnectionPath(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.MobileGeodatabaseConnectionPath.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>MobileGeodatabaseConnectionPath</code> class.</p>


```csharp
public MobileGeodatabaseConnectionPath(Uri path)
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.MobileGeodatabaseConnectionPath.yml" sourcestartlinenumber="1">The path to a mobile geodatabase that ends with the <i>.geodatabase</i> extension.</p>


```csharp
public Uri Path { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.MobileGeodatabaseConnectionPath.yml" sourcestartlinenumber="1">The type of mobile geodatabase.</p>


```csharp
public MobileGeodatabaseType Type { get; }
```


