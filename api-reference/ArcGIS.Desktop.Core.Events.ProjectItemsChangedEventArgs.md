# ProjectItemsChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEventArgs.yml" sourcestartlinenumber="1">Represents the project on which the ProjectItemsChangedEvent is operating</p>


## Object Signature

```csharp
public class ProjectItemsChangedEventArgs : EventArgs
```

## Remarks

<p>
    When the ProjectItemsChangedEvent is fired, ProjectItemsChangedEventArgs is returned to subscribers of the event
    </p>


## Members

### Action

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the action associated with the event that was fired</p>


```csharp
public NotifyCollectionChangedAction Action { get; }
```
### ProjectItem

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the project item associated with the event that was fired</p>


```csharp
public Item ProjectItem { get; }
```
### ProjectItemsCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of project items associated with the event that was fired</p>


```csharp
public List<Item> ProjectItemsCollection { get; }
```


