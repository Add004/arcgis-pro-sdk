# Host

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Hosting.html">Hosting</a>
- Assembly: ArcGIS.CoreHost.dll

<p sourcefile="api/ArcGIS.Core.Hosting.Host.yml" sourcestartlinenumber="1">Represents the Static Core Objects Host class. An instance of this class must be run before calling any classes in ArcGIS.Core.dll in an
external program (i.e. &quot;standalone&quot;)</p>


## Object Signature

```csharp
public class Host
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Hosting.Host.yml" sourcestartlinenumber="1">ArcGIS.Core.dll can be referenced in stand-alone projects that are <b>not</b> ArcGISPro Add-ins.</p>


## Members

### Initialize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Host.yml" sourcestartlinenumber="1">Call to initialize a Core Objects host process.  The method must be called
before constructing any objects from ArcGIS.CoreObjects library.</p>


```csharp
public static void Initialize()
```
### Initialize(LicenseProductCode)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Hosting.Host.yml" sourcestartlinenumber="1">Call to initialize a Core Objects host process.  The method must be called
before constructing any objects from ArcGIS.CoreObjects library.</p>


```csharp
public static void Initialize(Host.LicenseProductCode licenseProdCode)
```


