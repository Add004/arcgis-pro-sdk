# ToolOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Property collection that may be serialized to the CIM as a Template Tool's Options</p>


## Object Signature

```csharp
public sealed class ToolOptions : IDictionary<string, object>, ICollection<KeyValuePair<string, object>>, IEnumerable<KeyValuePair<string, object>>, IEnumerable, INotifyCollectionChanged, INotifyPropertyChanged, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">For the object values, only string and numeric types are supported for serialization, though currently there are no checks.<br><br>
Listening to the <xref href="ArcGIS.Desktop.Editing.ToolOptions.CollectionChanged" data-throw-if-not-resolved="false"></xref> event provides a way to share ToolOptions between a Tool and its corresponding ToolOptions EmbeddableControl.</p>


## Members

### Add(KeyValuePair&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Adds a new item to the collection.</p>


```csharp
public void Add(KeyValuePair<string, object> item)
```
### Add(string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Adds a new key value pair to the collection.</p>


```csharp
public void Add(string key, object value)
```
### Clear()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Clears the collection.</p>


```csharp
public void Clear()
```
### Contains(KeyValuePair&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets if the specified key value pair is in the collection.</p>


```csharp
public bool Contains(KeyValuePair<string, object> item)
```
### ContainsKey(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets if the specified key is in the collection.</p>


```csharp
public bool ContainsKey(string key)
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the number of items in the collection.</p>


```csharp
public int Count { get; }
```
### ~ToolOptions()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Property collection that may be serialized to the CIM as a Template Tool's Options</p>


```csharp
protected ~ToolOptions()
```
### GetProperty&lt;T&gt;(string, T)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Provide generic access to an option</p>


```csharp
public T GetProperty<T>(string key, T defaultValue = default)
```
### IsReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets if the collection is readonly.</p>


```csharp
public bool IsReadOnly { get; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the object in the collection referenced by the specified key.</p>


```csharp
public object this[string key] { get; set; }
```
### Keys

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the set of keys in the collection.</p>


```csharp
public ICollection<string> Keys { get; }
```
### Remove(KeyValuePair&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Removes the specified key value pair from the collection.</p>


```csharp
public bool Remove(KeyValuePair<string, object> item)
```
### Remove(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Removes the item specified by the key from the collection.</p>


```csharp
public bool Remove(string key)
```
### Template

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the Template associated with this ToolOptionsPropertySet</p>


```csharp
public EditingTemplate Template { get; }
```
### ToolID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the ToolID associated with this ToolOptionsPropertySet</p>


```csharp
public string ToolID { get; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ToolOptions.yml" sourcestartlinenumber="1">Gets the set of values in the collection.</p>


```csharp
public ICollection<object> Values { get; }
```


