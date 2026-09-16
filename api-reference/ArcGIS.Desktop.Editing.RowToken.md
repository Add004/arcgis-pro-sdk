# RowToken

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RowToken.yml" sourcestartlinenumber="1">A RowToken represents a feature that will be created but has not yet been created. It can be used in place of the object ID in referencing that feature even before it has an Object ID.</p>


## Object Signature

```csharp
public sealed class RowToken
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.RowToken.yml" sourcestartlinenumber="1">The RowToken can be used to chain together multiple editing primitives that depend on each other.  For example, you can create two rows using Create(), and use the
resulting RowTokens to create a utility network connectivity association.</p>


## Members

### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowToken.yml" sourcestartlinenumber="1">Gets the global ID of the feature, if it exists.</p>


```csharp
public Guid? GlobalID { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowToken.yml" sourcestartlinenumber="1">Gets the object ID of the feature, if it exists.</p>


```csharp
public long? ObjectID { get; }
```


