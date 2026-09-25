# GeometryObjectException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>.<a class="xref" href="ArcGIS.Core.Geometry.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.GeometryObjectException.yml" sourcestartlinenumber="1">Indicates there is a problem with a geometry parameter passed to a GeometryEngine function.  For example the geometry is empty or non Z-Aware (when passed to a function expecting a z-aware geometry).</p>


## Object Signature

```csharp
public class GeometryObjectException : GeometryException, ISerializable
```


## Members

### ExceptionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Exceptions.GeometryObjectException.yml" sourcestartlinenumber="1">Gets the type of the exception.  Always returns <xref href="ArcGIS.Core.Geometry.Exceptions.GeometryException.GeometryExceptionType.GeometryObjectException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override GeometryException.GeometryExceptionType ExceptionType { get; }
```


