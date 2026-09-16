# IArcGISSignOn

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">For use with CoreHost applications that need to authenticate with portal or arcgis online.</p>


## Object Signature

```csharp
public interface IArcGISSignOn
```

## Remarks

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Refer to <xref href="ArcGIS.Core.SystemCore.ArcGISSignOn" data-throw-if-not-resolved="false"></xref> for further details</p>


## Members

### GetFormattedPortalUri(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Ensures that a portal URI is formatted correctly.</p>


```csharp
Tuple<bool, Uri> GetFormattedPortalUri(Uri portalUri)
```
### IsSignedOn(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Check if the portal provided by the Uri is signed on. This method is for use in CoreHost applications only</p>


```csharp
bool IsSignedOn(Uri portalUri)
```
### SetSignonHandler(ISignOnHandler)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Set your SignOnHandler to receive challenge requests whenever a federated
feature service requires authentication. This method is for use in CoreHost applications only.</p>


```csharp
void SetSignonHandler(ISignOnHandler handler)
```
### SignInWithCredentials(Uri, string, string, out string, out string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Sign in to the portal provided by the Uri. This method is for use in CoreHost applications only</p>


```csharp
bool SignInWithCredentials(Uri portalUri, string user, string password, out string referer, out string token)
```
### SignOut(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.IArcGISSignOn.yml" sourcestartlinenumber="1">Sign out of the portal provided by the Uri. This method is for use in CoreHost applications only</p>


```csharp
void SignOut(Uri portalUri)
```


