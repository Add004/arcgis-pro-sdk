# IPresentationFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationFactory.yml" sourcestartlinenumber="1">Provides access to presentation creation members.</p>


## Object Signature

```csharp
public interface IPresentationFactory
```


## Members

### CopyPresentation(Presentation)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationFactory.yml" sourcestartlinenumber="1">Copies an existing presentation. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Presentation CopyPresentation(Presentation sourcePresentation)
```
### CreatePresentation()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationFactory.yml" sourcestartlinenumber="1">Creates a new empty presentation item and adds it to a project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Presentation CreatePresentation()
```
### CreatePresentation(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationFactory.yml" sourcestartlinenumber="1">Creates a new presentation presentation with a customized name and adds it to a project.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Presentation CreatePresentation(string name)
```


