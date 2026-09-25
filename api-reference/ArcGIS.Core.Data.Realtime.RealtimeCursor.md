# RealtimeCursor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursor.yml" sourcestartlinenumber="1">Represents a real-time cursor from a <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RealtimeCursor : RealtimeCursorBase, IDisposable
```


## Members

### Current

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursor.yml" sourcestartlinenumber="1">Gets the current <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RealtimeRow Current { get; }
```
### MoveNext()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RealtimeCursor.yml" sourcestartlinenumber="1">Advances to the next <xref href="ArcGIS.Core.Data.Realtime.RealtimeRow" data-throw-if-not-resolved="false"></xref> in this <xref href="ArcGIS.Core.Data.Realtime.RealtimeCursor" data-throw-if-not-resolved="false"></xref>.
This method can be called on any thread.</p>


```csharp
public bool MoveNext()
```


