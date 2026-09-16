# ItemCategory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ItemCategory.yml" sourcestartlinenumber="1">Provides a base class for ItemCategory classes defined in DAML</p>


## Object Signature

```csharp
public class ItemCategory
```

## Remarks

<p>
    An item category defines a collection of item types, and facilitates filtering a collection of items.
    An item category consists of a DAML declaration and a class derived from the ItemCategory class.
    For example, a category could define a relationship between the feature classes, relationship 
    classes and tables in a geodatabase. The item category allows you retrieve an enumerable collection 
    of items associated with the category at once from a given item. Use of the ItemCategory is not recursive.
    That is, when you retrieve items from a folder, the result will not include items stored within subfolders.
    </p>


## Members

### ItemCategory()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.ItemCategory.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Core.ItemCategory" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public ItemCategory()
```
### Items(IEnumerable&lt;Item&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ItemCategory.yml" sourcestartlinenumber="1">Returns an IEnumerable subset of items from an IEnumerable of items where the returned items participate in the Item Category.</p>


```csharp
public IEnumerable<Item> Items(IEnumerable<Item> items)
```


