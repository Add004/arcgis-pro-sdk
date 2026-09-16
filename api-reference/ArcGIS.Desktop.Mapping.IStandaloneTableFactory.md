# IStandaloneTableFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableFactory.yml" sourcestartlinenumber="1">StandaloneTable Factory interface for creating StandaloneTables. See <xref href="ArcGIS.Desktop.Mapping.StandaloneTableFactory" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public interface IStandaloneTableFactory
```


## Members

### CanCreateStandaloneTable(StandaloneTableCreationParams, IStandaloneTableContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableFactory.yml" sourcestartlinenumber="1">Indicates whether a StandaloneTable can be created using the specified StandaloneTableCreationParams and added to the container.</p>


```csharp
bool CanCreateStandaloneTable(StandaloneTableCreationParams tableParams, IStandaloneTableContainerEdit container)
```
### CanCreateStandaloneTableFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableFactory.yml" sourcestartlinenumber="1">Indicates whether a StandaloneTable can be created from an Item.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
bool CanCreateStandaloneTableFrom(Item item)
```
### CreateStandaloneTable(StandaloneTableCreationParams, IStandaloneTableContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableFactory.yml" sourcestartlinenumber="1">Creates a new StandaloneTable instance using the specified StandaloneTableCreationParams and adds it to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
StandaloneTable CreateStandaloneTable(StandaloneTableCreationParams tableParams, IStandaloneTableContainerEdit container)
```
### CreateStandaloneTable(Uri, IStandaloneTableContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IStandaloneTableFactory.yml" sourcestartlinenumber="1">Creates a new StandaloneTable instance with the specified path to a dataset and adds it to a container such as a map. Optionally you can provide a name to override the default display name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
StandaloneTable CreateStandaloneTable(Uri tableUri, IStandaloneTableContainerEdit container, int index = 0, string tableName = "")
```


