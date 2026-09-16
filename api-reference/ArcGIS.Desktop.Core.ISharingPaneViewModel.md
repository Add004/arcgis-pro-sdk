# ISharingPaneViewModel

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


## Object Signature

```csharp
public interface ISharingPaneViewModel
```


## Members

### CanShareToEveryOne

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
bool CanShareToEveryOne { get; }
```
### CanShareToOrganization

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
bool CanShareToOrganization { get; }
```
### ClearSelectedGroups()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
void ClearSelectedGroups()
```
### IsSignedIn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
bool IsSignedIn { get; set; }
```
### OrganizationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
string OrganizationName { get; set; }
```
### SelectedGroupIDs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
List<string> SelectedGroupIDs { get; }
```
### SelectedGroupNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
List<string> SelectedGroupNames { get; }
```
### SignedUserName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
string SignedUserName { get; set; }
```
### UpdateGroupItemsAsync(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
Task UpdateGroupItemsAsync(int connectionID = -1)
```
### UpdatePrivilegeAsync(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
Task UpdatePrivilegeAsync(int connectionID = -1)
```
### ValidGroupItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISharingPaneViewModel.yml" sourcestartlinenumber="1">Provides access to logic in ArcGIS.Desktop.Sharing.SharingPaneViewModel.</p>


```csharp
bool ValidGroupItems { get; }
```


