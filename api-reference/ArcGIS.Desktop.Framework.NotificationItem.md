# NotificationItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The class for notification item.</p>


## Object Signature

```csharp
public class NotificationItem
```


## Members

### NotificationItem(string, bool, string, NotificationType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The constructor to create a notification item.</p>


```csharp
public NotificationItem(string id, bool isApplicationLevel, string message, NotificationType type)
```
### NotificationItem(string, bool, string, NotificationType, string, bool, DateTime, string, string, Delegate, object[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The constructor to create a notification item.</p>


```csharp
[Obsolete]
public NotificationItem(string id, bool isApplicationLevel, string message, NotificationType type, string details = "", bool showContextMenu = true, DateTime date = default, string customImage = "", string customContextMenuItemText = "", Delegate customContextMenuItemDelegate = null, object[] contextMenuItemArgs = null)
```
### NotificationItem(string, bool, string, NotificationType, string, Delegate, object[], string, bool, string, DateTime, string, string, Delegate, object[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The constructor to create a notification item.</p>


```csharp
[Obsolete]
public NotificationItem(string id, bool isApplicationLevel, string message, NotificationType type, string actionText, Delegate action = null, object[] actionArgs = null, string details = "", bool showContextMenu = true, string helpContextID = null, DateTime date = default, string customImage = "", string customContextMenuItemText = "", Delegate customContextMenuItemDelegate = null, object[] contextMenuItemArgs = null)
```
### NotificationItem(string, bool, string, ImageSource, NotificationType, string, bool, DateTime, string, Delegate, object[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The constructor to create a notification item.</p>


```csharp
public NotificationItem(string id, bool isApplicationLevel, string message, ImageSource imageSource, NotificationType type, string details = "", bool showContextMenu = true, DateTime date = default, string customContextMenuItemText = "", Delegate customContextMenuItemDelegate = null, object[] contextMenuItemArgs = null)
```
### NotificationItem(string, bool, string, ImageSource, NotificationType, string, Delegate, object[], string, bool, string, DateTime, string, Delegate, object[])

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">The constructor to create a notification item.</p>


```csharp
public NotificationItem(string id, bool isApplicationLevel, string message, ImageSource imageSource, NotificationType type, string actionText, Delegate action = null, object[] actionArgs = null, string details = "", bool showContextMenu = true, string helpContextID = null, DateTime date = default, string customContextMenuItemText = "", Delegate customContextMenuItemDelegate = null, object[] contextMenuItemArgs = null)
```
### Action

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a custom handler specified to control what happens when a notification is clicked.</p>


```csharp
public Delegate Action { get; }
```
### ActionText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the text that shows the action the notification will perform on click.</p>


```csharp
public string ActionText { get; }
```
### Args

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the arguments associated with the action handler.</p>


```csharp
public object[] Args { get; }
```
### CustomContextMenuItemArgs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets arguments for the custom context menu item.</p>


```csharp
public object[] CustomContextMenuItemArgs { get; }
```
### CustomContextMenuItemDelegate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a custom handler assoicated with the custom menu item.</p>


```csharp
public Delegate CustomContextMenuItemDelegate { get; }
```
### CustomContextMenuItemText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a custom menu item that shows on the item's context menu.</p>


```csharp
public string CustomContextMenuItemText { get; }
```
### CustomImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the custom image of the notification item.</p>


```csharp
public object CustomImage { get; }
```
### Date

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the date displayed for the item.</p>


```csharp
public DateTime Date { get; }
```
### Details

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a detailed message.</p>


```csharp
public string Details { get; }
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a string value if the item shows in the Application or Project category.</p>


```csharp
public string Group { get; }
```
### HasHelpTopic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets wether the notification item has an associated help topic.</p>


```csharp
public bool HasHelpTopic { get; }
```
### HelpContextID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the help ID for the item.</p>


```csharp
public string HelpContextID { get; }
```
### HelpText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the text that shows for the help link.</p>


```csharp
public string HelpText { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a unique identifier of the notification item.</p>


```csharp
public string ID { get; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the general message of the notification item.</p>


```csharp
public string Message { get; }
```
### ShowContextMenu

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets a boolean value indicating if the notification item has an associated context menu.</p>


```csharp
public bool ShowContextMenu { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.NotificationItem.yml" sourcestartlinenumber="1">Gets the type of notification - Error, Warning, Confirmation, Information, or Custom.</p>


```csharp
public NotificationType Type { get; }
```


