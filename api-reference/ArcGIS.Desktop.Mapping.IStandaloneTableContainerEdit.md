# IStandaloneTableContainerEdit

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainerEdit.yml" sourcestartlinenumber="1">Provides access to StandaloneTables inside the container to modify.</p>


## Object Signature

```csharp
public interface IStandaloneTableContainerEdit : IStandaloneTableContainer
```


## Members

### MoveStandaloneTable(StandaloneTable, CompositeLayerWithTables, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainerEdit.yml" sourcestartlinenumber="1">Move a table to another layer container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void MoveStandaloneTable(StandaloneTable table, CompositeLayerWithTables targetLayer, int position)
```
### MoveStandaloneTable(StandaloneTable, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainerEdit.yml" sourcestartlinenumber="1">Move a table to another position within the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void MoveStandaloneTable(StandaloneTable table, int position)
```
### RemoveStandaloneTable(StandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainerEdit.yml" sourcestartlinenumber="1">Removes a StandaloneTable from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveStandaloneTable(StandaloneTable table)
```
### RemoveStandaloneTables(IEnumerable&lt;StandaloneTable&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainerEdit.yml" sourcestartlinenumber="1">Remove multiple StandaloneTable from the container.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RemoveStandaloneTables(IEnumerable<StandaloneTable> tables)
```


