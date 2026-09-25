# IMapPane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapPane.yml" sourcestartlinenumber="1">Represents a pane which contains a map view.</p>


## Object Signature

```csharp
public interface IMapPane
```


## Members

### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapPane.yml" sourcestartlinenumber="1">Gets or sets the caption for the pane.</p>


```csharp
string Caption { get; set; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapPane.yml" sourcestartlinenumber="1">Gets the map view contained within the pane.</p>


```csharp
MapView MapView { get; }
```
### ViewState

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IMapPane.yml" sourcestartlinenumber="1">Gets the definition of the view within the pane.</p>


```csharp
CIMMapView ViewState { get; }
```


