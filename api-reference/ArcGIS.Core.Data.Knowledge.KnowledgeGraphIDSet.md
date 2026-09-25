# KnowledgeGraphIDSet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">A collection of named object types and their corresponding list of records to represent a set of rows in a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphIDSet
```


## Members

### Contains(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Determines if the specified named object type is in the ID set.</p>


```csharp
public bool Contains(string namedObjectType)
```
### FromDictionary(KnowledgeGraph, Dictionary&lt;string, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromDictionary(KnowledgeGraph knowledgeGraph, Dictionary<string, List<long>> dict)
```
### FromDictionary(KnowledgeGraph, Dictionary&lt;string, List&lt;object&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromDictionary(KnowledgeGraph knowledgeGraph, Dictionary<string, List<object>> dict)
```
### FromDictionary(Uri, Dictionary&lt;string, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromDictionary(Uri knowledgeGraphPathOrServiceUri, Dictionary<string, List<long>> dict)
```
### FromDictionary(Uri, Dictionary&lt;string, List&lt;object&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromDictionary(Uri knowledgeGraphPathOrServiceUri, Dictionary<string, List<object>> dict)
```
### FromKnowledgeGraph(KnowledgeGraph, KnowledgeGraphFilterMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet with a particular filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromKnowledgeGraph(KnowledgeGraph knowledgeGraph, KnowledgeGraphFilterMethod filterMethod)
```
### FromKnowledgeGraph(Uri, KnowledgeGraphFilterMethod)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet with a particular filter.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphIDSet FromKnowledgeGraph(Uri knowledgeGraphPathOrServiceUri, KnowledgeGraphFilterMethod filterMethod)
```
### GetEntityRelationshipTypeNames()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Gets the list of entity and relationship types names in the ID set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (IReadOnlyList<string> entityTypeNames, IReadOnlyList<string> relationshipTypeNames) GetEntityRelationshipTypeNames()
```
### GetInvalidNamedTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Gets the set of invalid named types in the set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<string> GetInvalidNamedTypes()
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Gets if the ID set is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### NamedObjectTypeCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Gets the count of named object types in the ID set.</p>


```csharp
public int NamedObjectTypeCount { get; }
```
### ToOIDDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of named object types and their corresponding objectIDs.</p>


```csharp
public Dictionary<string, List<long>> ToOIDDictionary()
```
### ToUIDDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of named object types and their corresponding IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<string, List<object>> ToUIDDictionary()
```


