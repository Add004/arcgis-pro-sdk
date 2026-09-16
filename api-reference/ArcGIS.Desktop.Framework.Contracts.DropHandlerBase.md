# DropHandlerBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Represents a class that wants to process drag and drop operations. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class DropHandlerBase : IDropTarget
```

## Remarks

<p>
    This DropHandlerBase class provides little implementation, it satisfies the IDropTarget interface
    as simply as possible.
    </p>


## Members

### DropHandlerBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Represents a class that wants to process drag and drop operations. This is an abstract class.</p>


```csharp
protected DropHandlerBase()
```
### CreateDragAdorner(DataTemplate)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Allows the creation of a custom drag adorner</p>


```csharp
public virtual UIElement CreateDragAdorner(DataTemplate template)
```
### OnDragLeave()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Derived classes should override this function if they need to handle the mouse leaving the dragged over element</p>


```csharp
public virtual void OnDragLeave()
```
### OnDragOver(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Derived classes should override this function to process drag over events.</p>


```csharp
public virtual void OnDragOver(DropInfo dropInfo)
```
### OnDrop(DropInfo)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.DropHandlerBase.yml" sourcestartlinenumber="1">Derived classes should override this function to handle the drop operation.</p>


```csharp
public virtual void OnDrop(DropInfo dropInfo)
```


