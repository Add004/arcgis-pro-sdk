# SelectionSet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">A collection of mapMembers and their corresponding list of objectIDs to represent a set of rows or features that
are selected.</p>


## Object Signature

```csharp
public sealed class SelectionSet : MapMemberIDSet
```


## Members

### Equals(SelectionSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Determines whether the specified SelectionSet is equivalent to the current SelectionSet.</p>


```csharp
public bool Equals(SelectionSet other)
```
### Equals(object?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Determines whether the specified SelectionSet is equivalent to the current SelectionSet.</p>


```csharp
public override bool Equals(object? obj)
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, IList&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from the dictionary of records.</p>


```csharp
public static SelectionSet FromDictionary<T>(Dictionary<T, IList<long>> dict) where T : MapMember
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, List&lt;long&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from the dictionary of records.</p>


```csharp
public static SelectionSet FromDictionary<T>(Dictionary<T, List<long>> dict) where T : MapMember
```
### FromDictionary&lt;T&gt;(Dictionary&lt;T, long[]&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from the dictionary of records.</p>


```csharp
public static SelectionSet FromDictionary<T>(Dictionary<T, long[]> dict) where T : MapMember
```
### FromKnowledgeGraphIDSet(Map, KnowledgeGraphIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static SelectionSet FromKnowledgeGraphIDSet(Map map, KnowledgeGraphIDSet kgIDSet)
```
### FromKnowledgeGraphLayerIDSet(Map, KnowledgeGraphLayerIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from a KnowledgeGraphLayerIDSet.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet FromKnowledgeGraphLayerIDSet(Map map, KnowledgeGraphLayerIDSet kgLayerIDSet)
```
### FromMapMemberIDSet(MapMemberIDSet)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from a <xref href="ArcGIS.Desktop.Mapping.MapMemberIDSet" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static SelectionSet FromMapMemberIDSet(MapMemberIDSet mapMemberIDSet)
```
### FromSelection(MapMember, Selection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Creates a SelectionSet object from a given MapMember and a corresponding <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref>.
A Selection object is returned by some methods such as <xref href="ArcGIS.Desktop.Mapping.BasicFeatureLayer.GetSelection" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SelectionSet FromSelection(MapMember mapMember, Selection selection)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Serves as the default hash function.</p>


```csharp
public override int GetHashCode()
```
### operator ==(SelectionSet?, SelectionSet?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Desktop.Mapping.SelectionSet" data-throw-if-not-resolved="false"></xref> objects to determine whether they are equal.</p>


```csharp
public static bool operator ==(SelectionSet? left, SelectionSet? right)
```
### operator !=(SelectionSet?, SelectionSet?)

- Kind: operator

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionSet.yml" sourcestartlinenumber="1">Compares two <xref href="ArcGIS.Desktop.Mapping.SelectionSet" data-throw-if-not-resolved="false"></xref> objects to determine whether they are not equal.</p>


```csharp
public static bool operator !=(SelectionSet? left, SelectionSet? right)
```


