# TraverseManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Manages traverse operations.</p>


## Object Signature

```csharp
public sealed class TraverseManager
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Gets the TraverseManager.</p>


```csharp
public static TraverseManager Current { get; }
```
### GetTraverseAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Gets the contents of the traverse pane and grid and returns it as a <xref href="ArcGIS.Desktop.Editing.COGO.Traverse" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Task<Traverse> GetTraverseAsync()
```
### LoadTraverse(Traverse, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Loads a traverse into the traverse pane and grid.
This adds a single item to the undo stack. Specify the name of the operation using the <code class="paramref">operationName</code>.</p>


```csharp
public Task LoadTraverse(Traverse traverse, string operationName)
```
### LoadTraverse(Traverse, string, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Loads a traverse into the traverse pane and grid.
This adds a single item to the undo stack. Specify the name of the operation using the <code class="paramref">operationName</code>.</p>


```csharp
public Task LoadTraverse(Traverse traverse, string operationName, Layer layer)
```
### LoadTraverse(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Loads the specified ArcMap traverse file into the traverse pane and grid.
This adds a single item to the undo stack. Specify the name of the operation using the <code class="paramref">operationName</code>.</p>


```csharp
public Task LoadTraverse(string traverseFilePath, string operationName)
```
### LoadTraverse(string, string, Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseManager.yml" sourcestartlinenumber="1">Loads the specified ArcMap traverse file into the traverse pane and grid.
This adds a single item to the undo stack. Specify the name of the operation using the <code class="paramref">operationName</code>.</p>


```csharp
public Task LoadTraverse(string traverseFilePath, string operationName, Layer layer)
```


