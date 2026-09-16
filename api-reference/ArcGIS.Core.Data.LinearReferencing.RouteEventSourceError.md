# RouteEventSourceError

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.LinearReferencing.html">LinearReferencing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceError.yml" sourcestartlinenumber="1">Represents an error when locating an event along a route during <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref> creation or update, which uses a dynamic
segmentation process.</p>


## Object Signature

```csharp
public sealed class RouteEventSourceError
```


## Members

### LocatingErrorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceError.yml" sourcestartlinenumber="1">Gets the type of error associated with a row in the event table when using the dynamic segmentation process to locate the event along a route.</p>


```csharp
public LocatingErrorType LocatingErrorType { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceError.yml" sourcestartlinenumber="1">Gets the Object ID of the event.</p>


```csharp
public long ObjectID { get; }
```


