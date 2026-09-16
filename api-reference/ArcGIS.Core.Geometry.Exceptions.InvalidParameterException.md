# InvalidParameterException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>.<a class="xref" href="ArcGIS.Core.Geometry.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.InvalidParameterException.yml" sourcestartlinenumber="1">Thrown when a geometry engine parameter is invalid.</p>


## Object Signature

```csharp
public class InvalidParameterException : GeometryException, ISerializable
```


## Members

### ExceptionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.InvalidParameterException.yml" sourcestartlinenumber="1">Gets the type of the exception. Always returns <xref href="ArcGIS.Core.Geometry.Exceptions.GeometryException.GeometryExceptionType.InvalidParameterException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryException.GeometryExceptionType ExceptionType { get; }
```


