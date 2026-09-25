# LicensedApplication

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Licensing.html">Licensing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">Base class for the Pro application</p>


## Object Signature

```csharp
public abstract class LicensedApplication : FrameworkApplication
```


## Members

### LicensedApplication()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">Base class for the Pro application</p>


```csharp
protected LicensedApplication()
```
### ApplicationHasMonetizedExtensions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">Determines if the application has separately sold extension licenses for UI purposes</p>


```csharp
protected virtual bool ApplicationHasMonetizedExtensions { get; }
```
### InitializeLicensing()

- Kind: method


```csharp
protected Task InitializeLicensing()
```
### LicenseGuardMutexId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">GUID for license guard allowing only one sign in dialog for the application.</p>


```csharp
protected virtual string LicenseGuardMutexId { get; }
```
### ProcessProductCodes()

- Kind: method


```csharp
protected virtual void ProcessProductCodes()
```
### Shutdown()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">Shuts down the application.</p>


```csharp
public void Shutdown()
```
### Shutdown(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Licensing.LicensedApplication.yml" sourcestartlinenumber="1">Shuts down the application.</p>


```csharp
public void Shutdown(int exitCode)
```
### ValidateConfigurationManager()

- Kind: method


```csharp
protected virtual bool ValidateConfigurationManager()
```


