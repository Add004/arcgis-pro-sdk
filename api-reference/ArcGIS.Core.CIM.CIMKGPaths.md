# CIMKGPaths

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Represents the paths found by the Filtered Find Paths search.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="3">We use a memory-optimized representation to avoid storing redundant information because
it is often the case that a path shares some entities and relationships with many other paths,
especially if the Filtered Find Paths configuration uses 'KGPathMode.All'.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="7">Definition: a relationship group contains Knowledge Graph relationships associated to a single edge in the local graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="9">Paths are encoded this way:</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="11">The path 'p' uses relationships groups PathsBuffer[PathsEndIndex[p-1] .. PathsEndIndex[p]], and:</p>
<ul sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="12">
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="12">the origin of the first relationship group is the origin of the path</li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="13">the destination of the last relationship group is the destination of the path</li>
</ul>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="15">A path of length zero (with entity 'e') has a single relationship group containing no relationship and where the origin and the destination are 'e'.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="17">The relationships group 'g' has origin EntitiesUIDs[RelationshipsGroupsFrom[g]], destination EntitiesUIDs[RelationshipsGroupsTo[g]].
Its relationships are RelationshipsGroupsUIDsBuffer[RelationshipsGroupsUIDsEndIndex[g-1] .. RelationshipsGroupsUIDsEndIndex[g]].</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="20">The relationship RelationshipsGroupsUIDsBuffer[i] has a cost RelationshipsCosts[i].</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="22">if RelationshipsFrom[i] &gt;= 0, relationship RelationshipsGroupsUIDsBuffer[i] has origin EntitiesUIDs[RelationshipsFrom[i]]
else the relationship has been deleted after pathfinding.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="25">if RelationshipsTo[i] &gt;= 0, relationship RelationshipsGroupsUIDsBuffer[i] has destination EntitiesUIDs[RelationshipsTo[i]]
else the relationship has been deleted after pathfinding.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="28">Note that origin and destination of a relationship may not match origin and destination of the relationship group
because the relationship can be traversed backwards.</p>


## Object Signature

```csharp
public class CIMKGPaths : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGPaths()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Represents the paths found by the Filtered Find Paths search.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="3">We use a memory-optimized representation to avoid storing redundant information because
it is often the case that a path shares some entities and relationships with many other paths,
especially if the Filtered Find Paths configuration uses 'KGPathMode.All'.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="7">Definition: a relationship group contains Knowledge Graph relationships associated to a single edge in the local graph.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="9">Paths are encoded this way:</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="11">The path 'p' uses relationships groups PathsBuffer[PathsEndIndex[p-1] .. PathsEndIndex[p]], and:</p>
<ul sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="12">
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="12">the origin of the first relationship group is the origin of the path</li>
<li sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="13">the destination of the last relationship group is the destination of the path</li>
</ul>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="15">A path of length zero (with entity 'e') has a single relationship group containing no relationship and where the origin and the destination are 'e'.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="17">The relationships group 'g' has origin EntitiesUIDs[RelationshipsGroupsFrom[g]], destination EntitiesUIDs[RelationshipsGroupsTo[g]].
Its relationships are RelationshipsGroupsUIDsBuffer[RelationshipsGroupsUIDsEndIndex[g-1] .. RelationshipsGroupsUIDsEndIndex[g]].</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="20">The relationship RelationshipsGroupsUIDsBuffer[i] has a cost RelationshipsCosts[i].</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="22">if RelationshipsFrom[i] &gt;= 0, relationship RelationshipsGroupsUIDsBuffer[i] has origin EntitiesUIDs[RelationshipsFrom[i]]
else the relationship has been deleted after pathfinding.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="25">if RelationshipsTo[i] &gt;= 0, relationship RelationshipsGroupsUIDsBuffer[i] has destination EntitiesUIDs[RelationshipsTo[i]]
else the relationship has been deleted after pathfinding.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="28">Note that origin and destination of a relationship may not match origin and destination of the relationship group
because the relationship can be traversed backwards.</p>


```csharp
public CIMKGPaths()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGPaths.</p>


```csharp
public CIMKGPaths Clone()
```
### EntitiesUIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of entities that may be used in paths (not all entities are guaranteed to be used).</p>


```csharp
public object[] EntitiesUIDs { get; set; }
```
### EntityTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets a list parallel to EntitiesUIDs representing entity type indices.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="3">if EntityTypes[i] &gt;= 0, EntitiesUIDs[i] has type IndexedEntityTypes[EntityTypes[i]]
else the entity has been deleted after the find path operation.</p>


```csharp
public long[] EntityTypes { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Reconstructs the CIMKGPaths with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGPaths FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndexedEntityTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of entity types, indexed by 'EntityTypes'.</p>


```csharp
public string[] IndexedEntityTypes { get; set; }
```
### IndexedRelationshipTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationship types, indexed by 'RelationshipTypes'.</p>


```csharp
public string[] IndexedRelationshipTypes { get; set; }
```
### PathsBuffer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships groups indices used by paths. Values must be positive.</p>


```csharp
public long[] PathsBuffer { get; set; }
```
### PathsEndIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of paths relationships groups end indices (indexes into 'PathsBuffer'). Values must be positive.</p>


```csharp
public long[] PathsEndIndex { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets a list parallel to RelationshipsGroupsUIDsBuffer representing relationship type indices.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="3">if RelationshipTypes[i] &gt;= 0, RelationshipsGroupsUIDsBuffer[i] has type IndexedRelationshipTypes[RelationshipTypes[i]]
else the relationship has been deleted after the find path operation.</p>


```csharp
public long[] RelationshipTypes { get; set; }
```
### RelationshipsCosts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships cost.</p>


```csharp
public double[] RelationshipsCosts { get; set; }
```
### RelationshipsFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships origin entity index (indexes into 'EntitiesUIDs').</p>


```csharp
public long[] RelationshipsFrom { get; set; }
```
### RelationshipsGroupsFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships groups origin entity index (indexes into 'EntitiesUIDs'). Values must be positive.</p>


```csharp
public long[] RelationshipsGroupsFrom { get; set; }
```
### RelationshipsGroupsTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships groups destination entity index (indexes into 'EntitiesUIDs'). Values must be positive.</p>


```csharp
public long[] RelationshipsGroupsTo { get; set; }
```
### RelationshipsGroupsUIDsBuffer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships that may be used in paths (not all relationships are guaranteed to be used).
The list may contain duplicate elements.</p>


```csharp
public object[] RelationshipsGroupsUIDsBuffer { get; set; }
```
### RelationshipsGroupsUIDsEndIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships groups relationship end indices (indexes into 'RelationshipsGroupsUIDsBuffer'). Values must be positive.</p>


```csharp
public long[] RelationshipsGroupsUIDsEndIndex { get; set; }
```
### RelationshipsTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Gets or sets the list of relationships destination entity index (indexes into 'EntitiesUIDs').</p>


```csharp
public long[] RelationshipsTo { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGPaths and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGPaths.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


