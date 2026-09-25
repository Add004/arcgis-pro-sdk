# NotificationManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">A class for managing notifications on a dockable window.</p>


## Object Signature

```csharp
public class NotificationManager : PropertyChangedBase, INotifyPropertyChanged
```


## Members

### AddNotification(NotificationItem)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Add a notifcation item.</p>


```csharp
public static void AddNotification(NotificationItem item)
```
### ClearNotification()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Clear all notifications on the dockable window.</p>


```csharp
public static void ClearNotification()
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Gets the number of notifications.</p>


```csharp
public static int Count { get; }
```
### IgnoreList

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Gets the list of ignored notifications.</p>


```csharp
public static string[] IgnoreList { get; }
```
### NotificationDisabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating if the notifications are disabled.</p>


```csharp
public static bool NotificationDisabled { get; }
```
### NotificationItems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Gets or sets all the notification items on the dockable window.</p>


```csharp
public ObservableCollection<NotificationItem> NotificationItems { get; set; }
```
### RemoveNotification(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationManager.yml" sourcestartlinenumber="1">Remove the notification by id.</p>


```csharp
public static bool RemoveNotification(string id)
```


