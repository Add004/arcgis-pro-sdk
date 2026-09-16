# IElementContainer

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Identifies the implementor of being the parent
of one or more <b>Elements</b></p>


## Object Signature

```csharp
public interface IElementContainer
```


## Members

### ClearElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Clears all the elements from the collection.</p>


```csharp
void ClearElements()
```
### FindElement(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Finds the element specified by name.</p>


```csharp
IElement FindElement(string elementName, bool recurse = true)
```
### GetElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Gets the collection of elements in the container.</p>


```csharp
IReadOnlyList<IElement> GetElements()
```
### GetFlattenedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Gets the flattened collection of elements in the container.</p>


```csharp
IReadOnlyList<IElement> GetFlattenedElements()
```
### GetSelectedElements()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Gets the collection of currently selected elements</p>


```csharp
IReadOnlyList<IElement> GetSelectedElements()
```
### InsertElement(IElement, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Inserts a new element at the specified position.</p>


```csharp
void InsertElement(IElement element, int index = -1)
```
### MoveElement(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Moves the element specified by name to the new index.</p>


```csharp
void MoveElement(string elementName, int newIndex)
```
### RemoveElement(string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Removes the element specified by name.</p>


```csharp
void RemoveElement(string elementName, bool recurse = true)
```
### SelectElements(Geometry, SelectionCombinationMethod, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Select elements with matching names</p>


```csharp
void SelectElements(Geometry geometry, SelectionCombinationMethod method, bool isWhollyWithin)
```
### SelectElements(IEnumerable&lt;string&gt;, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Select elements with matching names</p>


```csharp
void SelectElements(IEnumerable<string> names, bool syncViewer = true, bool syncTOC = true)
```
### UnselectElements(IEnumerable&lt;string&gt;, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IElementContainer.yml" sourcestartlinenumber="1">Unselect elements with matching names</p>


```csharp
void UnselectElements(IEnumerable<string> names, bool syncViewer = true, bool syncTOC = true)
```


