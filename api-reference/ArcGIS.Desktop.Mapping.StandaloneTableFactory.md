# StandaloneTableFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Provides static methods to create StandaloneTables.</p>


## Object Signature

```csharp
public class StandaloneTableFactory : IStandaloneTableFactory
```


## Members

### CanCreateStandaloneTable(StandaloneTableCreationParams, IStandaloneTableContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Indicates whether a StandaloneTable can be created using the specified StandaloneTableCreationParams and added to the container.</p>


```csharp
public bool CanCreateStandaloneTable(StandaloneTableCreationParams tableParams, IStandaloneTableContainerEdit container)
```
### CanCreateStandaloneTableFrom(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Indicates whether a StandaloneTable can be created from an Item.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool CanCreateStandaloneTableFrom(Item item)
```
### CreateStandaloneTable(StandaloneTableCreationParams, IStandaloneTableContainerEdit)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Creates a new StandaloneTable instance using the specified StandaloneTableCreationParams and adds it to a container such as a map.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public StandaloneTable CreateStandaloneTable(StandaloneTableCreationParams tableParams, IStandaloneTableContainerEdit container)
```
### CreateStandaloneTable(Uri, IStandaloneTableContainerEdit, int, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Creates a new StandaloneTable instance with the specified path to a dataset and adds it to a container such as a map. Optionally you can provide a name to override the default display name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public StandaloneTable CreateStandaloneTable(Uri tableUri, IStandaloneTableContainerEdit container, int index = 0, string tableName = "")
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableFactory.yml" sourcestartlinenumber="1">Gets the singleton instance for IStandaloneTableFactory.</p>


```csharp
public static IStandaloneTableFactory Instance { get; }
```


