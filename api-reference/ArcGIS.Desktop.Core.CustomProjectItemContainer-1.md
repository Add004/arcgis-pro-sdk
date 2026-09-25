# CustomProjectItemContainer&lt;T&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">A custom project item container contains custom project items of a specific type that have been
added to a project.</p>


## Object Signature

```csharp
public abstract class CustomProjectItemContainer<T> : ProjectItemContainer<T>, IMetadata, IReadOnlyList<T>, IReadOnlyCollection<T>, IEnumerable<T>, IEnumerable, IDisposable, ISearchableItem where T : CustomProjectItemBase
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">By default, empty project item containers are not visible in the
Catalog pane or view. They only become visible once they contain at least one (custom)
project item. Custom project item containers are registered in the Config.daml
within the <b>esri_core_projectContainers</b> category. Custom project item containers
have an associated &quot;<i>container type</i>&quot; which is an arbitrary unique string
used to identify your container within the project container collection.<br>Custom project
items must know their corresponding custom project item container container type.</p>


## Members

### CustomProjectItemContainer(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
public CustomProjectItemContainer(string containerType)
```
### CreateItem(string, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">Create a project item. CreateItem is called when items are being added to the project.</p>


```csharp
public override Item CreateItem(string name, string path, string containerType, string data)
```
### CreateItemPrototype(string, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">Provides a factory method for custom project item containers to create custom project
items of its contained type.</p>


```csharp
public override Item CreateItemPrototype(string name, string path, string containerType, string data)
```
### LargeImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">Gets the large image to use when displaying the container</p>


```csharp
public virtual ImageSource LargeImage { get; }
```
### SmallImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.CustomProjectItemContainer-1.yml" sourcestartlinenumber="1">Gets the small image to use when displaying the container</p>


```csharp
public virtual Task<ImageSource> SmallImage { get; }
```


