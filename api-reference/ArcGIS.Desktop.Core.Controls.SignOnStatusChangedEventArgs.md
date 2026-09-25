# SignOnStatusChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnStatusChangedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the SignOnStatusChanged event for the
SignOnControl.</p>


## Object Signature

```csharp
public sealed class SignOnStatusChangedEventArgs : EventArgs
```


## Members

### CurrentPortalUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnStatusChangedEventArgs.yml" sourcestartlinenumber="1">Gets the current portal uri.</p>


```csharp
public string CurrentPortalUri { get; }
```
### IsSignedIn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnStatusChangedEventArgs.yml" sourcestartlinenumber="1">Gets the signed in status.</p>


```csharp
public bool IsSignedIn { get; }
```
### SignedOnUserName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnStatusChangedEventArgs.yml" sourcestartlinenumber="1">Gets the current signed on user name.  If <xref href="ArcGIS.Desktop.Core.Controls.SignOnStatusChangedEventArgs.IsSignedIn" data-throw-if-not-resolved="false"></xref> is false, this is the empty string.</p>


```csharp
public string SignedOnUserName { get; }
```


