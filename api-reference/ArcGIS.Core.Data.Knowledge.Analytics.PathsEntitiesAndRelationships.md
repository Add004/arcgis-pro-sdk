# PathsEntitiesAndRelationships

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.Analytics.html">Analytics</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Represents entities and relationships used in paths.</p>


## Object Signature

```csharp
public class PathsEntitiesAndRelationships
```


## Members

### EntitiesUIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the UIDs of entities used in paths.</p>


```csharp
public object[] EntitiesUIDs { get; }
```
### EntityTypeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the entity type names indexed by EntityTypes.</p>


```csharp
public string[] EntityTypeNames { get; }
```
### EntityTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the index of the entity type within the EntityTypeNames array for
each entity in EntitiesUIDs.</p>


```csharp
public ulong[] EntityTypes { get; }
```
### PathsDestinationEntitiesUIDsIndexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the indexes (into EntitiesUIDs) of paths destination entities.</p>


```csharp
public ulong[] PathsDestinationEntitiesUIDsIndexes { get; }
```
### PathsOriginEntitiesUIDsIndexes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the indexes (into EntitiesUIDs) of paths origin entities.</p>


```csharp
public ulong[] PathsOriginEntitiesUIDsIndexes { get; }
```
### RelationshipTypeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the relationship type names indexed by RelationshipTypes.</p>


```csharp
public string[] RelationshipTypeNames { get; }
```
### RelationshipTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the index of the relationship type within the RelationshipTypeNames array for
each relationship in RelationshipsUIDs.</p>


```csharp
public ulong[] RelationshipTypes { get; }
```
### RelationshipsFrom

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the indexes (into EntitiesUIDs) of relationships origin entities.</p>


```csharp
public ulong[] RelationshipsFrom { get; }
```
### RelationshipsTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the indexes (into EntitiesUIDs) of relationships destination entities.</p>


```csharp
public ulong[] RelationshipsTo { get; }
```
### RelationshipsUIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Gets the UIDs of relationships used in paths.</p>


```csharp
public object[] RelationshipsUIDs { get; }
```
### ToKnowledgeGraphIDSet(KGResultContentFromFFP)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.Analytics.PathsEntitiesAndRelationships.yml" sourcestartlinenumber="1">Converts the entities and relationships from the FFP results into a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphIDSet" data-throw-if-not-resolved="false"></xref>.<br></p>


```csharp
public KnowledgeGraphIDSet ToKnowledgeGraphIDSet(KGResultContentFromFFP resultContent)
```


