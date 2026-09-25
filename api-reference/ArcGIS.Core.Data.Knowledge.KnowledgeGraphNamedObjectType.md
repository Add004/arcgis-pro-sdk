# KnowledgeGraphNamedObjectType

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Abstract base class representing a named object type.
Concrete subclasses include <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphEntityType" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphRelationshipType" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class KnowledgeGraphNamedObjectType : CoreObjectsBase, IDisposable
```


## Members

### GetAliasName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the alias name for this named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAliasName()
```
### GetHasObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets a boolean indicating whether the named object type has an ObjectID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetHasObjectID()
```
### GetIsSpatial()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets if the named object type has spatial information associated with it.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsSpatial()
```
### GetIsStrict()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Get a boolean indicating whether the named object type is strict
in the data model. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsStrict()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the name of the named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetObjectIDPropertyName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the name of the graph property representing the ObjectID
for this named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetObjectIDPropertyName()
```
### GetProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Get the list of properties on this named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<KnowledgeGraphProperty> GetProperties()
```
### GetRole()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the role of the named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public KnowledgeGraphNamedObjectTypeRole GetRole()
```
### GetShapeDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Geometry.GeometryType" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref> for the shape column of the named object type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (GeometryType geometryType, SpatialReference sr) GetShapeDefinition()
```
### GetShapeField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectType.yml" sourcestartlinenumber="1">Gets the name of the field where the shape (geometry) is stored.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetShapeField()
```


