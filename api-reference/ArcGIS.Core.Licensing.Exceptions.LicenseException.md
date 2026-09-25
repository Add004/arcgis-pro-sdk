# LicenseException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Licensing.html">Licensing</a>.<a class="xref" href="ArcGIS.Core.Licensing.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Licensing.Exceptions.LicenseException.yml" sourcestartlinenumber="1">Represents a licensing error - typically Pro is running with an insufficient license to eexcute a tool.
For exmample Pro is running under a Basic license but your tool requires a Standard license.</p>


## Object Signature

```csharp
public class LicenseException : Exception, ISerializable
```


## Members

### LicenseException(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Licensing.Exceptions.LicenseException.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>LicenseException</code> class with a specified error message.</p>


```csharp
public LicenseException(string message)
```
### LicenseException(string, Exception)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Licensing.Exceptions.LicenseException.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>LicenseException</code> class
with a specified error message and a reference to the inner exception that is the cause of this exception.</p>


```csharp
public LicenseException(string message, Exception innerException)
```


