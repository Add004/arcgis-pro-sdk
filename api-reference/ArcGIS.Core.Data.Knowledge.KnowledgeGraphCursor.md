# KnowledgeGraphCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Represents an object returned by a query or text search performed
on a knowledge graph.</p>


## Object Signature

```csharp
public class KnowledgeGraphCursor : RealtimeCursorBase, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow" data-throw-if-not-resolved="false"></xref> in the graph row cursor.</p>


```csharp
public KnowledgeGraphRow Current { get; }
```
### FindKey(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Gets the index of the specified key.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindKey(string keyName)
```
### GetError()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Get an error object with an error code and error message from the cursor.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphServerError GetError()
```
### GetHasError()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Get a boolean indicating whether the cursor has an error.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetHasError()
```
### GetKeys()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Gets the readonly list of keys associated with the original query string.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetKeys()
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRow" data-throw-if-not-resolved="false"></xref> in the graph row cursor.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool MoveNext()
```


