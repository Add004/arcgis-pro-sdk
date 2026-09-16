# RealtimeFeature

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeature.yml" sourcestartlinenumber="1">Represents a feature in a <xref href="ArcGIS.Core.Data.Realtime.RealtimeFeatureClass" data-throw-if-not-resolved="false"></xref> returned by <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class RealtimeFeature : RealtimeRow, IDisposable
```


## Members

### GetShape()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeature.yml" sourcestartlinenumber="1">Gets the geometry of this feature.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Geometry GetShape()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeFeature.yml" sourcestartlinenumber="1">Gets and sets the value of a field given its index position.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public override object this[int index] { get; }
```


