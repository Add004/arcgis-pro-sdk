# ConstructedOnWrongThreadException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.ConstructedOnWrongThreadException.yml" sourcestartlinenumber="1">Thrown when a fine-grained object is being created on the wrong Pro thread</p>


## Object Signature

```csharp
public class ConstructedOnWrongThreadException : Exception, ISerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.ConstructedOnWrongThreadException.yml" sourcestartlinenumber="1">Usually this means an object that needs to be created on the Pro background thread
is, instead, trying to be created from the UI</p>


## Members

### ConstructedOnWrongThreadException()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.ConstructedOnWrongThreadException.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ConstructedOnWrongThreadException()
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Core.ConstructedOnWrongThreadException.yml" sourcestartlinenumber="1">Gets the associated exception message</p>


```csharp
public override string Message { get; }
```


