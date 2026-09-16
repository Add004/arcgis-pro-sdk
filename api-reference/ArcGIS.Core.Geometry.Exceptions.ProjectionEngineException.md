# ProjectionEngineException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>.<a class="xref" href="ArcGIS.Core.Geometry.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.ProjectionEngineException.yml" sourcestartlinenumber="1">Thrown when there is a problem with the projection engine.</p>


## Object Signature

```csharp
public class ProjectionEngineException : GeometryException, ISerializable
```


## Members

### ExceptionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.ProjectionEngineException.yml" sourcestartlinenumber="1">Gets the type of the exception. Always returns <xref href="ArcGIS.Core.Geometry.Exceptions.GeometryException.GeometryExceptionType.ProjectionEngineException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryException.GeometryExceptionType ExceptionType { get; }
```


