# CalledOnWrongThreadException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CalledOnWrongThreadException.yml" sourcestartlinenumber="1">Thrown when a method is called on the wrong Pro thread</p>


## Object Signature

```csharp
public class CalledOnWrongThreadException : Exception, ISerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CalledOnWrongThreadException.yml" sourcestartlinenumber="1">Usually this means a method that must be called on the Pro background thread is
called from the UI</p>


## Members

### CalledOnWrongThreadException()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CalledOnWrongThreadException.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public CalledOnWrongThreadException()
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Core.CalledOnWrongThreadException.yml" sourcestartlinenumber="1">Gets the associated exception message</p>


```csharp
public override string Message { get; }
```


