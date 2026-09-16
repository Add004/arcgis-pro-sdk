# IStandaloneTableContainer

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainer.yml" sourcestartlinenumber="1">Provides read-only access to StandaloneTables inside the container.</p>


## Object Signature

```csharp
public interface IStandaloneTableContainer
```


## Members

### FindStandaloneTable(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainer.yml" sourcestartlinenumber="1">Finds a StandaloneTable using a URI. Child group layers are also searched.</p>


```csharp
StandaloneTable FindStandaloneTable(string tableURI)
```
### FindStandaloneTables(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainer.yml" sourcestartlinenumber="1">Finds StandaloneTables by name. Child group layers are also searched.</p>


```csharp
IReadOnlyList<StandaloneTable> FindStandaloneTables(string name)
```
### GetSnapshot()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainer.yml" sourcestartlinenumber="1">Returns a read-only snapshot of the tables in the container.</p>


```csharp
IReadOnlyList<StandaloneTable> GetSnapshot()
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableContainer.yml" sourcestartlinenumber="1">Gets a read-only collection of StandaloneTables from the container.</p>


```csharp
ReadOnlyObservableCollection<StandaloneTable> StandaloneTables { get; }
```


