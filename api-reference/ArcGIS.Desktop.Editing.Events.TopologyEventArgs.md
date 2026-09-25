# TopologyEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.TopologyEventArgs.yml" sourcestartlinenumber="1">Represents the current change in topology state.</p>


## Object Signature

```csharp
public sealed class TopologyEventArgs : EventArgs
```


## Members

### CurrentTopology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.TopologyEventArgs.yml" sourcestartlinenumber="1">Gets the current topology value.</p>


```csharp
public Tuple<string, bool, double> CurrentTopology { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.TopologyEventArgs.yml" sourcestartlinenumber="1">Gets the Map.</p>


```csharp
public Map Map { get; }
```
### NewTopology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.TopologyEventArgs.yml" sourcestartlinenumber="1">Gets the new topology value.</p>


```csharp
public Tuple<string, bool, double> NewTopology { get; }
```


