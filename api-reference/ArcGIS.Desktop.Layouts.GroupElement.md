# GroupElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.GroupElement.yml" sourcestartlinenumber="1">Represents a group element that appears in the layout contents pane.</p>


## Object Signature

```csharp
public class GroupElement : Element, IEquatable<Element>, IComparable, IElement, IElementInternal, IDisposable, IElementContainer, IElementContainerInternal, ISuspendableObservableCollection
```

## Remarks

<p>
    It is possible that group elements can be nested in another group element. If the element container is a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref> 
    then the element gets added to the root level of the layout TOC at the top most position.  If the element container is a 
    <xref href="ArcGIS.Desktop.Layouts.GroupElement?text=GroupElement" data-throw-if-not-resolved="false"></xref> then it gets added to the group at the topmost position. 
    </p>
<p>
    The <xref href="ArcGIS.Desktop.Layouts.Layout.FindElement?text=FindElement" data-throw-if-not-resolved="false"></xref> method will also find elements nested in a group element.
    </p>
<p>
    If you want to work with all the elements within a group element, use the <xref href="ArcGIS.Desktop.Layouts.GroupElement.Elements?text=Elements" data-throw-if-not-resolved="false"></xref> property to 
    return the collection of elements in a group element.  
    </p>


## Members

### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.GroupElement.yml" sourcestartlinenumber="1">Gets the read-only collection of child elements</p>


```csharp
public ReadOnlyObservableCollection<Element> Elements { get; }
```
### GetElementsAsFlattenedList()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.GroupElement.yml" sourcestartlinenumber="1">Get the collection of <xref href="ArcGIS.Desktop.Layouts.Element" data-throw-if-not-resolved="false"></xref> from the group element as a flattened list.
Nested groups within child <xref href="ArcGIS.Desktop.Layouts.GroupElement" data-throw-if-not-resolved="false"></xref> are <b>not</b> preserved.</p>


```csharp
public IReadOnlyList<Element> GetElementsAsFlattenedList()
```
### IsLocked

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.GroupElement.yml" sourcestartlinenumber="1">Gets if the element is locked.</p>


```csharp
public override bool IsLocked { get; }
```


