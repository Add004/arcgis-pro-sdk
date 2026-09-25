# SignInResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.SignInResult.yml" sourcestartlinenumber="1">Contains the status of the <xref href="ArcGIS.Desktop.Core.ArcGISPortal.SignIn?text=Portal+SignIn" data-throw-if-not-resolved="false"></xref>. This
includes the success of failure of the SignIn and the current token (if succesfull)</p>


## Object Signature

```csharp
public class SignInResult
```


## Members

### success

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SignInResult.yml" sourcestartlinenumber="1">Gets the success of the portal SignOn</p>


```csharp
public bool success { get; }
```
### token

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.SignInResult.yml" sourcestartlinenumber="1">Gets the current token.</p>


```csharp
public string token { get; }
```


