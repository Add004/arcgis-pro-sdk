# IGridOptionsEnvironment

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Provides access to the grid options for application maps.</p>


## Object Signature

```csharp
public interface IGridOptionsEnvironment
```


## Members

### ClearGridOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Clears all grid options for all maps in the Project. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void ClearGridOptions()
```
### DefaultGridOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets a set of default grid options</p>


```csharp
GridOptions DefaultGridOptions { get; }
```
### GetGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Get the grid options for the given map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GridOptions GetGridOptions(Map map)
```
### GetGridOptions(Map, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Get the grid options for the given map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GridOptions GetGridOptions(Map map, bool add)
```
### HasGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets whether a map currently has any grid options</p>


```csharp
bool HasGridOptions(Map map)
```
### Refresh()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Triggers a refresh of the current grid overlay.</p>


```csharp
void Refresh()
```
### RemoveGridOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Removes the grid options for the specified map. This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveGridOptions(Map map)
```
### SetGridOptions(Map, GridOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Set the grid options for the given map.This method must
be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void SetGridOptions(Map map, GridOptions gridOptions)
```
### ShowGrid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IGridOptionsEnvironment.yml" sourcestartlinenumber="1">Gets and sets whether or not to show a grid on application map views</p>


```csharp
bool ShowGrid { get; set; }
```


