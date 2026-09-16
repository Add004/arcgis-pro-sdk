# KnowledgeGraphLayerIDSet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">A collection of named object types and their corresponding list of records to represent a set of rows in a <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayer" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphLayerIDSet
```


## Members

### Contains(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Determines if the specified named object type is in the ID set.</p>


```csharp
public bool Contains(string namedObjectType)
```
### FromDictionary(KnowledgeGraph, Dictionary&lt;string, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromDictionary(KnowledgeGraph knowledgeGraph, Dictionary<string, List<long>> dict)
```
### FromDictionary(KnowledgeGraph, Dictionary&lt;string, List&lt;object&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromDictionary(KnowledgeGraph knowledgeGraph, Dictionary<string, List<object>> dict)
```
### FromDictionary(Uri, Dictionary&lt;string, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromDictionary(Uri knowledgeGraphPathOrServiceUri, Dictionary<string, List<long>> dict)
```
### FromDictionary(Uri, Dictionary&lt;string, List&lt;object&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet object from a dictionary of records.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromDictionary(Uri knowledgeGraphPathOrServiceUri, Dictionary<string, List<object>> dict)
```
### FromKnowledgeGraph(KnowledgeGraph, KnowledgeGraphFilterType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet with a particular filter type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromKnowledgeGraph(KnowledgeGraph knowledgeGraph, KnowledgeGraphFilterType filterType)
```
### FromKnowledgeGraph(Uri, KnowledgeGraphFilterType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet with a particular filter type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromKnowledgeGraph(Uri knowledgeGraphPathOrServiceUri, KnowledgeGraphFilterType filterType)
```
### FromKnowledgeGraphIDSet(KnowledgeGraphIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet from a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromKnowledgeGraphIDSet(KnowledgeGraphIDSet idSet)
```
### FromMapMemberIDSet(MapMemberIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet from a <xref href="ArcGIS.Desktop.Mapping.MapMemberIDSet" data-throw-if-not-resolved="false"></xref>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromMapMemberIDSet(MapMemberIDSet mapMemberIDSet)
```
### FromSelectionSet(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphLayerIDSet from a selection set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static KnowledgeGraphLayerIDSet FromSelectionSet(SelectionSet selection)
```
### GetEntityRelationshipTypeNames()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Gets the list of entity and relationship types names in the set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (IReadOnlyList<string> entityTypeNames, IReadOnlyList<string> relationshipTypeNames) GetEntityRelationshipTypeNames()
```
### GetInvalidNamedTypes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Gets the set of invalid named types in the set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public List<string> GetInvalidNamedTypes()
```
### IDSet

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphIDSet IDSet { get; }
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Gets if the ID set is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### NamedObjectTypeCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Gets the count of named object types in the ID set.</p>


```csharp
public int NamedObjectTypeCount { get; }
```
### ToOIDDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of named object types and their corresponding objectIDs.</p>


```csharp
public Dictionary<string, List<long>> ToOIDDictionary()
```
### ToUIDDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of named object types and their corresponding IDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Dictionary<string, List<object>> ToUIDDictionary()
```


