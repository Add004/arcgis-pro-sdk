# SignOnControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">The SignOnControl provides a UI for signing in or out of ArcGIS Online or any portal.</p>


## Object Signature

```csharp
public class SignOnControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```


## Members

### SignOnControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the SignOnControl is hosted.</p>


```csharp
public SignOnControl()
```
### ActivePortalUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the active portal Uri.</p>


```csharp
public string ActivePortalUri { get; }
```
### ActivePortalUriProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the active portal Uri.</p>


```csharp
public static readonly DependencyProperty ActivePortalUriProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsSignedIn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets whether the <xref href="ArcGIS.Desktop.Core.Controls.SignOnControl" data-throw-if-not-resolved="false"></xref> is signed in or not.</p>


```csharp
public bool IsSignedIn { get; }
```
### IsSignedInProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets whether the SignOnControl is signed in (IsSignedIn is true).</p>


```csharp
public static readonly DependencyProperty IsSignedInProperty
```
### SignOnStatusChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">The SignOnStatusChanged event is raised when the sign on status changes.  A change consists of signing in or out of the current portal.</p>


```csharp
public event SignOnControl.SignOnStatusChangedEventHandler SignOnStatusChanged
```
### SignedOnDisplayName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user display name. If not signed in, then an empty string is returned.</p>


```csharp
public string SignedOnDisplayName { get; }
```
### SignedOnDisplayNameProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user display name. If not signed in, then an empty string is returned.</p>


```csharp
public static readonly DependencyProperty SignedOnDisplayNameProperty
```
### SignedOnFullName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user full name. If not signed in, then an empty string is returned.</p>


```csharp
public string SignedOnFullName { get; }
```
### SignedOnFullNameProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user full name. If not signed in, then an empty string is returned.</p>


```csharp
public static readonly DependencyProperty SignedOnFullNameProperty
```
### SignedOnInitials

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user initials. If not signed in, then an empty string is returned.</p>


```csharp
public string SignedOnInitials { get; }
```
### SignedOnInitialsProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user initials. If not signed in, then an empty string is returned.</p>


```csharp
public static readonly DependencyProperty SignedOnInitialsProperty
```
### SignedOnOrganizationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the signed on organization name. If not signed in, then the organization name of the active portal is returned..</p>


```csharp
public string SignedOnOrganizationName { get; }
```
### SignedOnOrganizationNameProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the signed on organization name. If not signed in, then the organization name of the active portal is returned..</p>


```csharp
public static readonly DependencyProperty SignedOnOrganizationNameProperty
```
### SignedOnUserName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user name. If not signed in, then an empty string is returned.</p>


```csharp
public string SignedOnUserName { get; }
```
### SignedOnUserNameProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.Controls.SignOnControl.yml" sourcestartlinenumber="1">Gets the currently signed on user name. If not signed in, then an empty string is returned.</p>


```csharp
public static readonly DependencyProperty SignedOnUserNameProperty
```


