# ILayoutPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutPane.yml" sourcestartlinenumber="1">Represents a pane which contains a layout view.</p>


## Object Signature

```csharp
public interface ILayoutPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane the way it appears on the tab.</p>


```csharp
string Caption { get; set; }
```
### LayoutView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutPane.yml" sourcestartlinenumber="1">Gets the layout view contained within the pane.</p>


```csharp
LayoutView LayoutView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ILayoutPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMLayoutView ViewState { get; }
```


