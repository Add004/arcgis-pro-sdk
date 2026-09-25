# OperationException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>.<a class="xref" href="ArcGIS.Core.Geometry.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.OperationException.yml" sourcestartlinenumber="1">Thrown when a geometry operation fails.</p>


## Object Signature

```csharp
public class OperationException : GeometryException, ISerializable
```


## Members

### ExceptionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.OperationException.yml" sourcestartlinenumber="1">Gets the type of the exception. Always returns <xref href="ArcGIS.Core.Geometry.Exceptions.GeometryException.GeometryExceptionType.OperationException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryException.GeometryExceptionType ExceptionType { get; }
```


