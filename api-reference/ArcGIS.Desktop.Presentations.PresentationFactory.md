# PresentationFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationFactory.yml" sourcestartlinenumber="1">Provides methods to create new presentation project items.</p>


## Object Signature

```csharp
public class PresentationFactory : IPresentationFactory
```

## Remarks

<p>
    Creating a new presentation generates a new presentation project item that appears in the Presentation folder in the Contents pane.  
    </p>
<p>
    A new presentation project item is not automatically opened in a presentation view pane.  
    </p>


## Members

### CopyPresentation(Presentation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationFactory.yml" sourcestartlinenumber="1">Copies an existing presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Presentation CopyPresentation(Presentation sourcePresentation)
```
### CreatePresentation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationFactory.yml" sourcestartlinenumber="1">Creates a new empty presentation item and adds it to a project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Presentation CreatePresentation()
```
### CreatePresentation(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationFactory.yml" sourcestartlinenumber="1">Creates a new presentation without any pages and adds it to a project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Presentation CreatePresentation(string name)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.PresentationFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IPresentationFactory</p>


```csharp
public static IPresentationFactory Instance { get; }
```


