# MapMemberIDSet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">A collection of mapMembers and their corresponding list of objectIDs to represent a set of rows or features.</p>


## Object Signature

```csharp
public class MapMemberIDSet
```


## Members

### Contains(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Determines if records from the specified mapMember are in the MapMemberIDSet.</p>


```csharp
public bool Contains(MapMember mapMember)
```
### Contains(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Determines if the record specified by the mapMember and oid pair is in the MapMemberIDSet.</p>


```csharp
public bool Contains(MapMember mapMember, long oid)
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Gets the total count of records in the MapMemberIDSet.</p>


```csharp
public int Count { get; }
```
### Equals(MapMemberIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Determines whether the specified MapMemberIDSet is equivalent to the current MapMemberIDSet.</p>


```csharp
public bool Equals(MapMemberIDSet other)
```
### Equals(object?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Determines whether the specified MapMemberIDSet is equivalent to the current MapMemberIDSet.</p>


```csharp
public override bool Equals(object? obj)
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, HashSet&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a MapMemberIDSet object from the dictionary of records.</p>


```csharp
public static MapMemberIDSet FromDictionary<T>(Dictionary<T, HashSet<long>> dict) where T : MapMember
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, IList&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a MapMemberIDSet object from the dictionary of records.</p>


```csharp
public static MapMemberIDSet FromDictionary<T>(Dictionary<T, IList<long>> dict) where T : MapMember
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a MapMemberIDSet object from the dictionary of records.</p>


```csharp
public static MapMemberIDSet FromDictionary<T>(Dictionary<T, List<long>> dict) where T : MapMember
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, long[]&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a MapMemberIDSet object from the dictionary of records.</p>


```csharp
public static MapMemberIDSet FromDictionary<T>(Dictionary<T, long[]> dict) where T : MapMember
```
### FromKnowledgeGraphIDSet(Map, KnowledgeGraphIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Desktop.Mapping.MapMemberIDSet" data-throw-if-not-resolved="false"></xref> object from a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static MapMemberIDSet FromKnowledgeGraphIDSet(Map map, KnowledgeGraphIDSet kgIDSet)
```
### FromKnowledgeGraphLayerIDSet(Map, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a MapMemberIDSet object from a KnowledgeGraphLayerIDSet.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static MapMemberIDSet FromKnowledgeGraphLayerIDSet(Map map, KnowledgeGraphLayerIDSet kgLayerIDSet)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### IsEmpty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Gets if the MapMemberIDSet is empty.</p>


```csharp
public bool IsEmpty { get; }
```
### this[MapMember]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Gets the list of objectIDs that are contained in the MapMemberIDSet associated with the specified mapMember.</p>


```csharp
public IList<long> this[MapMember mapMember] { get; }
```
### ToDictionary()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of mapMembers and their corresponding objectIDs.</p>


```csharp
public Dictionary<MapMember, List<long>> ToDictionary()
```
### ToDictionary&lt;T&gt;()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates the dictionary of mapMembers and their corresponding objectIDs.</p>


```csharp
public Dictionary<T, List<long>> ToDictionary<T>() where T : MapMember
```
### ToKnowledgeGraphIDSet()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Creates a KnowledgeGraphIDSet from this MapMemberIDSet.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphIDSet ToKnowledgeGraphIDSet()
```
### operator ==(MapMemberIDSet?, MapMemberIDSet?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Desktop.Mapping.MapMemberIDSet" data-throw-if-not-resolved="false"></xref> objects to determine whether they are equal.</p>


```csharp
public static bool operator ==(MapMemberIDSet? left, MapMemberIDSet? right)
```
### operator !=(MapMemberIDSet?, MapMemberIDSet?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberIDSet.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Desktop.Mapping.MapMemberIDSet" data-throw-if-not-resolved="false"></xref> objects to determine whether they are not equal.</p>


```csharp
public static bool operator !=(MapMemberIDSet? left, MapMemberIDSet? right)
```


