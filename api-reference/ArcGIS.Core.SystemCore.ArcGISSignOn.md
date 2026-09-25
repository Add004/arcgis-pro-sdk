# ArcGISSignOn

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">For use with CoreHost applications that need to authenticate with portal or arcgis online.</p>


## Object Signature

```csharp
public class ArcGISSignOn : IArcGISSignOn
```

## Remarks

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Use this class to provide credentials to connect to federated services within
CoreHost applications. Attempting to use this class within an Addin will throw
a <xref href="System.InvalidOperationException" data-throw-if-not-resolved="false"></xref></p>


## Members

### GetFormattedPortalUri(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Ensures that a portal URI is formatted correctly.</p>


```csharp
public Tuple<bool, Uri> GetFormattedPortalUri(Uri portalUri)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Gets the singleton instance for ArcGISSignOn</p>


```csharp
public static IArcGISSignOn Instance { get; }
```
### IsSignedOn(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Check if the portal provided by the Uri is signed on. This method is for use in CoreHost applications only</p>


```csharp
public bool IsSignedOn(Uri portalUri)
```
### SetSignonHandler(ISignOnHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Set your SignOnHandler to receive challenge requests whenever a federated
feature service requires authentication. This method is for use in CoreHost applications only.</p>


```csharp
public void SetSignonHandler(ISignOnHandler handler)
```
### SignInWithCredentials(Uri, string, string, out string, out string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Sign in to the portal provided by the Uri. This method is for use in CoreHost applications only</p>


```csharp
public bool SignInWithCredentials(Uri portalUri, string user, string password, out string referer, out string token)
```
### SignOut(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.ArcGISSignOn.yml" sourcestartlinenumber="1">Sign out of the portal provided by the Uri. This method is for use in CoreHost applications only</p>


```csharp
public void SignOut(Uri portalUri)
```


