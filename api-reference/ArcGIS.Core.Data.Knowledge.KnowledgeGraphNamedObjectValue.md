# KnowledgeGraphNamedObjectValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Represents a named object value from a KnowledgeGraph. Named objects can
be either entities or relationships.</p>


## Object Signature

```csharp
public abstract class KnowledgeGraphNamedObjectValue : KnowledgeGraphObjectValue, IDisposable
```


## Members

### GetHasObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Gets whether the named graph object has an ObjectID or not.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual bool GetHasObjectID()
```
### GetID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Gets the ID associated with the named object value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual object GetID()
```
### GetObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Gets the ObjectID or -1 if the named object does not have one.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual long GetObjectID()
```
### GetTypeName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Knowledge.KnowledgeGraphNamedObjectValue.yml" sourcestartlinenumber="1">Gets the named object Type name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public virtual string GetTypeName()
```


