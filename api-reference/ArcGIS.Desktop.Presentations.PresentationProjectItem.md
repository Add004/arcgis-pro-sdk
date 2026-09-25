# PresentationProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationProjectItem.yml" sourcestartlinenumber="1">Presentation project item</p>


## Object Signature

```csharp
public sealed class PresentationProjectItem : ProjectItem, IProjectItemEdit, IProjectItemRename, IPortalProjectItem
```


## Members

### DisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationProjectItem.yml" sourcestartlinenumber="1">Gets the item display type string.</p>


```csharp
protected override string DisplayType { get; }
```
### GetPresentation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationProjectItem.yml" sourcestartlinenumber="1">Loads and returns the <xref href="ArcGIS.Desktop.Presentations.Presentation?text=Presentation" data-throw-if-not-resolved="false"></xref> associated with the PresentationProjectItem. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Presentation GetPresentation()
```
### OnOpenView()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationProjectItem.yml" sourcestartlinenumber="1">Called when a project item is double-clicked by project item framework and
by the module when a user right-click and selects open.</p>


```csharp
protected override void OnOpenView()
```


