# CompositeLayerWithTables

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Represents an abstract class for a read-only collection of layers and display tables.</p>


## Object Signature

```csharp
public abstract class CompositeLayerWithTables : CompositeLayer, IMetadataInfo, IMetadataSource, ILayerContainer, IStandaloneTableContainer
```


## Members

### CompositeLayerWithTables()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected CompositeLayerWithTables()
```
### FindStandaloneTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Finds a StandaloneTable using a URI. Child group layers are also searched.</p>


```csharp
public StandaloneTable FindStandaloneTable(string tableURI)
```
### FindStandaloneTables(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Finds StandaloneTables by name. Child group layers are also searched.</p>


```csharp
public IReadOnlyList<StandaloneTable> FindStandaloneTables(string name)
```
### GetMapMembersAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Returns a read only flat list of mapMembers where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<MapMember> GetMapMembersAsFlattenedList()
```
### GetStandaloneTablesAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Returns a read only flat list of StandaloneTables where nested groups are not preserved.</p>


```csharp
public IReadOnlyList<StandaloneTable> GetStandaloneTablesAsFlattenedList()
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.CompositeLayerWithTables.yml" sourcestartlinenumber="1">Gets a read-only collection of StandaloneTables from the composite layer with tables.</p>


```csharp
public ReadOnlyObservableCollection<StandaloneTable> StandaloneTables { get; }
```


