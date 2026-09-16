# ReadOnlyToolOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">A read-only wrapper for <xref href="ArcGIS.Desktop.Editing.ToolOptions" data-throw-if-not-resolved="false"></xref> made available by <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.GetToolOptions(System.String)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class ReadOnlyToolOptions : IDisposable
```


## Members

### ContainsKey(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">Gets if the specified key is in the collection.</p>


```csharp
public bool ContainsKey(string key)
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">Gets the number of items in the collection.</p>


```csharp
public int Count { get; }
```
### ~ReadOnlyToolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">A read-only wrapper for <xref href="ArcGIS.Desktop.Editing.ToolOptions" data-throw-if-not-resolved="false"></xref> made available by <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.GetToolOptions(System.String)" data-throw-if-not-resolved="false"></xref></p>


```csharp
protected ~ReadOnlyToolOptions()
```
### GetProperty&lt;T&gt;(string, T)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">provide generic access to an option</p>


```csharp
public T GetProperty<T>(string key, T defaultValue = default)
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">Gets the object in the collection referenced by the specified key.</p>


```csharp
public object this[string key] { get; }
```
### Keys

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">Gets the set of keys in the collection.</p>


```csharp
public IReadOnlyList<string> Keys { get; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ReadOnlyToolOptions.yml" sourcestartlinenumber="1">Gets the set of values in the collection.</p>


```csharp
public IReadOnlyList<object> Values { get; }
```


