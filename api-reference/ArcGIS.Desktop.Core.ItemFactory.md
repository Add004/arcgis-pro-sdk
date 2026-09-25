# ItemFactory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Creates items that can be added or imported to the project</p>


## Object Signature

```csharp
public class ItemFactory : IItemFactory
```


## Members

### CanGetDataset(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets if the dataset for the item can be retrieved.</p>


```csharp
public bool CanGetDataset(Item item)
```
### CanGetDefinition(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets if the definition for the item can be retrieved.</p>


```csharp
public bool CanGetDefinition(Item item)
```
### CanGetKnowledgeGraphNamedObjectType(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets if the Knowledge Graph named object type for the item can be retrieved.</p>


```csharp
public bool CanGetKnowledgeGraphNamedObjectType(Item item)
```
### Create(string, ItemType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref> representing the resource identified by the Uri</p>


```csharp
public Item Create(string uri, ItemFactory.ItemType itemType = ItemType.PathItem)
```
### GetDataset(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> associated with the item corresponding to <xref href="ArcGIS.Desktop.Core.Item.Path" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dataset GetDataset(Item item)
```
### GetDatasetType(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.DatasetType" data-throw-if-not-resolved="false"></xref> for the item. If the dataset type cannot be determined, then <xref href="ArcGIS.Core.Data.DatasetType.Unknown" data-throw-if-not-resolved="false"></xref> is returned.</p>


```csharp
public DatasetType GetDatasetType(Item item)
```
### GetDefinition(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Definition" data-throw-if-not-resolved="false"></xref> associated with the item corresponding to <xref href="ArcGIS.Desktop.Core.Item.Path" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Definition GetDefinition(Item item)
```
### GetKnowledgeGraphNamedObjectType(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType" data-throw-if-not-resolved="false"></xref> associated with the item corresponding to <xref href="ArcGIS.Desktop.Core.Item.Path" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphNamedObjectType GetKnowledgeGraphNamedObjectType(Item item)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Gets the IItemFactory instance</p>


```csharp
public static IItemFactory Instance { get; }
```
### IsCustomItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Determines whether the item is a custom item or not.</p>


```csharp
public bool IsCustomItem(Item item)
```
### IsCustomItem(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemFactory.yml" sourcestartlinenumber="1">Determines whether the path points to a custom item or not.</p>


```csharp
public bool IsCustomItem(string uri)
```


