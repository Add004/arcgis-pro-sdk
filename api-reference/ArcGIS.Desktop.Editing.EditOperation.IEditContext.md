# EditOperation.IEditContext

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Interface of the context given to an edit callback to invalidate features within an edit.</p>


## Object Signature

```csharp
public interface EditOperation.IEditContext
```


## Members

### Abort()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Abort the callback.</p>


```csharp
void Abort()
```
### Abort(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Abort the callback and set the errorMessage.</p>


```csharp
void Abort(string errorMessage)
```
### Invalidate(Dataset)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Invalidates all features/rows in a dataset.</p>


```csharp
void Invalidate(Dataset dataset)
```
### Invalidate(Relationship)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Invalidates the map in response to a relationship being modified.</p>


```csharp
void Invalidate(Relationship relationship)
```
### Invalidate(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.EditOperation.IEditContext.yml" sourcestartlinenumber="1">Invalidates a feature/row.</p>


```csharp
void Invalidate(Row row)
```


