# IExternalTablePane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IExternalTablePane.yml" sourcestartlinenumber="1">Represents a pane which contains a table view populated with data from an Item within a geodatabase.</p>


## Object Signature

```csharp
public interface IExternalTablePane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IExternalTablePane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane.</p>


```csharp
string Caption { get; set; }
```
### TableView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IExternalTablePane.yml" sourcestartlinenumber="1">Gets the table view contained within the pane.</p>


```csharp
TableView TableView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IExternalTablePane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMExternalTableView ViewState { get; }
```


