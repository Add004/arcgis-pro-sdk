# KnowledgeGraphArrayValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Represents an array of knowledge graph values in a KnowledgeGraph.</p>


## Object Signature

```csharp
public class KnowledgeGraphArrayValue : KnowledgeGraphValue, IDisposable
```


## Members

### KnowledgeGraphArrayValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public KnowledgeGraphArrayValue()
```
### Add(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Add a value to the end of the array. This method must be
called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Add(object value)
```
### AddRange(IList)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Add a collection of values to the end of the array. This method must be
called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void AddRange(IList collection)
```
### GetSize()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Gets the number of values in the graph array.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ulong GetSize()
```
### this[ulong]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphArrayValue.yml" sourcestartlinenumber="1">Gets and sets the value from/for the array of values given its index position.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object this[ulong index] { get; set; }
```


