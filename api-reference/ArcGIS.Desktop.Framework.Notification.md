# Notification

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Represents a toast style notification.</p>


## Object Signature

```csharp
public class Notification : INotifyPropertyChanged
```

## Remarks

<p>
    A toast notification is a transient message to the user that contains relevant, time-sensitive 
    information and provides quick access to related content in an application. Notifications appear 
    in the top right hand corner of the display and last for a few seconds unless the mouse pointer 
    is over the top of them. Up to four notifications can appear at the same time. If more than four notifications 
    are sent, each new notification bumps off the oldest one in the queue.
    </p>
<p>
    Use <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.AddNotification(ArcGIS.Desktop.Framework.Notification)" data-throw-if-not-resolved="false"></xref> to pop-up a new notification.
    </p>


## Members

### Notification()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Framework.Notification" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Notification()
```
### Notification(NotificationLevel, NotificationType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Initializes an instance of the <xref href="ArcGIS.Desktop.Framework.Notification" data-throw-if-not-resolved="false"></xref> class
with an option to auto convey toast notifications to the notification pane</p>


```csharp
public Notification(Notification.NotificationLevel level, NotificationType type)
```
### HasHelpTopic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets if there is a help topic link.</p>


```csharp
public bool HasHelpTopic { get; }
```
### HelpText

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the text accompanying the HelpTopic (if set).
Default value is &quot;Learn More...&quot;</p>


```csharp
public string HelpText { get; set; }
```
### HelpTopic

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the Help topic link. A help topic link is optional for a notification.</p>


```csharp
public string HelpTopic { get; set; }
```
### Id

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets the framework assigned Id.</p>


```csharp
public int Id { get; }
```
### ImageSource

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the image to show. ImageUrl must be null for this property to work properly.</p>


```csharp
public ImageSource ImageSource { get; set; }
```
### ImageUrl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the image to show. Use ImageSource if you have a resource.</p>


```csharp
public string ImageUrl { get; set; }
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the message.</p>


```csharp
public string Message { get; set; }
```
### OnClick()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Occurs when a notification message is clicked by the user.</p>


```csharp
protected virtual void OnClick()
```
### OnHelpTextClicked()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Occurs when the HelpText is clicked by the user.</p>


```csharp
protected virtual void OnHelpTextClicked()
```
### OnHyperlinkCommand(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Occurs when a notification's message is in rich text format (RTF),
and the user clicks on the hyperlink that triggers a command.</p>


```csharp
protected virtual void OnHyperlinkCommand(string commandName)
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Occurs when a property is updated.</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```
### Severity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the Toast notification severity.</p>


```csharp
public Notification.SeverityLevel Severity { get; set; }
```
### TimeStamp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the TimeStamp.</p>


```csharp
public DateTime TimeStamp { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Notification.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```


