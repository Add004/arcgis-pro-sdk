# ISearchableItem

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ISearchableItem.yml" sourcestartlinenumber="1">ISearchableItem interface</p>


## Object Signature

```csharp
public interface ISearchableItem
```


## Members

### RequiresMainThread

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ISearchableItem.yml" sourcestartlinenumber="1">Gets if the main thread is required</p>


```csharp
bool RequiresMainThread { get; }
```
### Search(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ISearchableItem.yml" sourcestartlinenumber="1">Search method</p>


```csharp
IEnumerable<Item> Search(string searchString)
```


