# ParcelRecordEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ParcelRecordEventArgs.yml" sourcestartlinenumber="1">Represents the current change in parcel record state.</p>


## Object Signature

```csharp
public sealed class ParcelRecordEventArgs : EventArgs
```


## Members

### IncomingActiveRecord

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ParcelRecordEventArgs.yml" sourcestartlinenumber="1">The record that becomes newly active with this event.</p>


```csharp
public ParcelRecord IncomingActiveRecord { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ParcelRecordEventArgs.yml" sourcestartlinenumber="1">The Map.</p>


```csharp
public Map Map { get; }
```
### OutgoingActiveRecord

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.ParcelRecordEventArgs.yml" sourcestartlinenumber="1">The record that had been active before this event.</p>


```csharp
public ParcelRecord OutgoingActiveRecord { get; }
```


