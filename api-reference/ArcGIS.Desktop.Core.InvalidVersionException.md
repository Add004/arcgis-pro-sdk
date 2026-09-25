# InvalidVersionException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.InvalidVersionException.yml" sourcestartlinenumber="1">Represents the managed exception base class for custom ArcGIS.Desktop.Core exceptions</p>


## Object Signature

```csharp
public class InvalidVersionException : Exception, ISerializable
```


## Members

### ExceptionType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.InvalidVersionException.yml" sourcestartlinenumber="1">Specifies the exception types that may occur when attempting to use a project or project template,
a map or layout file, or a package</p>


```csharp
public virtual InvalidVersionException.Type ExceptionType { get; }
```


