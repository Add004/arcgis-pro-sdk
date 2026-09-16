# MessageBox

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Dialogs.html">Dialogs</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Represents a dialog box for simple messages.</p>


## Object Signature

```csharp
public class MessageBox
```


## Members

### Show(ref bool, string, Window, string, string, MessageBoxButton, MessageBoxImage, MessageBoxResult, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a checkbox where users may
opt to disable its appearance in the future.<br>
The message box also displays a message, title bar caption, button, and icon.
The caller may also specify a default message box result.
On return, the ref Boolean argument will be set to true if the checkbox was checked by the user.</p>


```csharp
public static MessageBoxResult Show(ref bool noRemind, string checkBoxMessage, Window owner, string messageText, string caption, MessageBoxButton button, MessageBoxImage icon, MessageBoxResult defaultResult, string helpContextID = "")
```
### Show(ref bool, string, Window, string, string, MessageBoxButton, MessageBoxImage, MessageBoxResult, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a checkbox where users may
opt to disable its appearance in the future.<br>
The message box also displays a message, title bar caption, button, and icon.
The caller may also specify a default message box result.
On return, the ref Boolean argument will be set to true if the checkbox was checked by the user.</p>


```csharp
public static MessageBoxResult Show(ref bool noRemind, string checkBoxMessage, Window owner, string messageText, string caption, MessageBoxButton button, MessageBoxImage icon, MessageBoxResult defaultResult, string moreInfoText, string helpContextID = "", string helpLinkText = "")
```
### Show(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box that has a message and that returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText)
```
### Show(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box that has a message and title bar caption; and that returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText, string caption)
```
### Show(string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box that has a message and title bar caption; and that returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText, string caption, string helpContextID)
```
### Show(string, string, MessageBoxButton)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box that has a message, title bar caption, and button; and that returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText, string caption, MessageBoxButton button)
```
### Show(string, string, MessageBoxButton, MessageBoxImage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box that has a message, title bar caption, button, and icon; and that returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText, string caption, MessageBoxButton button, MessageBoxImage icon)
```
### Show(string, string, MessageBoxButton, MessageBoxImage, MessageBoxResult)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message, title bar caption, button, and icon;
and accepts a default message box result and returns a result.</p>


```csharp
public static MessageBoxResult Show(string messageText, string caption, MessageBoxButton button, MessageBoxImage icon, MessageBoxResult defaultResult)
```
### Show(Window, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message and returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText)
```
### Show(Window, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message and title bar caption; and it returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText, string caption)
```
### Show(Window, string, string, MessageBoxButton)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message, title bar caption, button, and icon; and it also returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText, string caption, MessageBoxButton button)
```
### Show(Window, string, string, MessageBoxButton, MessageBoxImage)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message, title bar caption, button, and icon;
and it also returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText, string caption, MessageBoxButton button, MessageBoxImage icon)
```
### Show(Window, string, string, MessageBoxButton, MessageBoxImage, MessageBoxResult, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message, title bar caption, button, and icon;
and accepts a default message box result, complies with the specified options, and returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText, string caption, MessageBoxButton button, MessageBoxImage icon, MessageBoxResult defaultResult, string helpContextID = "")
```
### Show(Window, string, string, MessageBoxButton, MessageBoxImage, MessageBoxResult, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Dialogs.MessageBox.yml" sourcestartlinenumber="1">Displays a message box in front of the specified window. The message box displays a message, title bar caption, button, and icon;
and accepts a default message box result, complies with the specified options, and returns a result.</p>


```csharp
public static MessageBoxResult Show(Window owner, string messageText, string caption, MessageBoxButton button, MessageBoxImage icon, MessageBoxResult defaultResult, string moreInfoText, string helpContextID = "", string helpLinkText = "")
```


