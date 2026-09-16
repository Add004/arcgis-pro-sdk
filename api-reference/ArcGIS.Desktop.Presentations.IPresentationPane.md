# IPresentationPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Presentations.html">Presentations</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPane.yml" sourcestartlinenumber="1">Represents a pane which contains a presentation view.</p>


## Object Signature

```csharp
public interface IPresentationPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane the way it appears on the tab.</p>


```csharp
string Caption { get; set; }
```
### PresentationView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPane.yml" sourcestartlinenumber="1">Gets the presentation view contained within the pane.</p>


```csharp
PresentationView PresentationView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Presentations.IPresentationPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMView ViewState { get; }
```


