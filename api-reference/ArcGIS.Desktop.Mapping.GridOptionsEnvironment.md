# GridOptionsEnvironment

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Provides access to the grid options for application maps.</p>


## Object Signature

```csharp
public class GridOptionsEnvironment : IGridOptionsEnvironment
```


## Members

### ClearGridOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Clears all grid options for all maps in the Project. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void ClearGridOptions()
```
### DefaultGridOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets a set of default grid options</p>


```csharp
public GridOptions DefaultGridOptions { get; }
```
### GetGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Get the grid options for the given map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GridOptions GetGridOptions(Map map)
```
### GetGridOptions(Map, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Get the grid options for the given map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public GridOptions GetGridOptions(Map map, bool add)
```
### HasGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets whether a map currently has any grid options</p>


```csharp
public bool HasGridOptions(Map map)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets the singleton instance for IGridOptionsEnvironment.</p>


```csharp
public static IGridOptionsEnvironment Instance { get; }
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Triggers a refresh of the current grid overlay.</p>


```csharp
public void Refresh()
```
### RemoveGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Removes the grid options for the specified map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void RemoveGridOptions(Map map)
```
### SetGridOptions(Map, GridOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Set the grid options for the given map.This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetGridOptions(Map map, GridOptions gridOptions)
```
### ShowGrid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.GridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets and sets whether or not to show a grid on application map views</p>


```csharp
public bool ShowGrid { get; set; }
```


