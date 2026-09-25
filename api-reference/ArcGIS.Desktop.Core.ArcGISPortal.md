# ArcGISPortal

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">The ArcGISPortal class is part of the Pro Portal API which provides a way to build applications
that work with content from ArcGIS Online or an ArcGIS Portal. ArcGIS Portal is software technology
from Esri that customers can deploy either on premise or in the cloud. ArcGIS Online is
Esri's Software as a Service offering that represents GIS as a Service and is implemented using
the same technology as ArcGIS Portal. The Portal API allows application developers to work with users,
groups and content hosted within ArcGIS Online or within an ArcGIS Portal.</p>


## Object Signature

```csharp
public class ArcGISPortal
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">ArcGISPortal instances are instantiated using the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref> and
its <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager.AddPortal(System.Uri)" data-throw-if-not-resolved="false"></xref> method.<br></p>


## Members

### EnsureValid()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Ensure the portal is a valid.</p>


```csharp
public void EnsureValid()
```
### GetSignOnUsername()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets the username for the current connection
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public string GetSignOnUsername()
```
### GetToken()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets the current token for the session. The ArcGISPortal class automatically manages
the token expiration. This value should not be cached.
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public string GetToken()
```
### IsActivePortal()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets whether this portal instance is the active portal</p>


```csharp
public bool IsActivePortal()
```
### IsPortalAvailable()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets whether this portal instance is avilable to connect to its end point.</p>


```csharp
public bool IsPortalAvailable()
```
### IsSignedOn()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets the sign on status of the portal instance.
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public bool IsSignedOn()
```
### PortalUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Gets the portal Uri for this portal instance</p>


```csharp
public Uri PortalUri { get; }
```
### SignIn()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Synchronous method to Sign on to this portal instance.</p>


```csharp
public SignInResult SignIn()
```
### SignInAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Asynchronous method to Sign on to this portal instance.</p>


```csharp
public Task<SignInResult> SignInAsync()
```
### SignInWithCredentials(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Synchronous method to Sign on to this portal instance.
This method must be called from within a QueuedTask or BackgroundTask.</p>


```csharp
public SignInResult SignInWithCredentials(string username, string password)
```
### SignOut()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortal.yml" sourcestartlinenumber="1">Sign out from this portal instance
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public bool SignOut()
```


