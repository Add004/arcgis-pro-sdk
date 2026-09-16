# DynamicSpatialFilterUpdatedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.DynamicSpatialFilterUpdatedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.DynamicSpatialFilterUpdatedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class DynamicSpatialFilterUpdatedEventArgs : EventArgs
```


## Members

### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.DynamicSpatialFilterUpdatedEventArgs.yml" sourcestartlinenumber="1">Gets the map containing the affected members.</p>


```csharp
public Map Map { get; }
```
### MapMembers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.DynamicSpatialFilterUpdatedEventArgs.yml" sourcestartlinenumber="1">Gets the map members affected by dependent spatial definition invalidation.</p>


```csharp
public IList<MapMember> MapMembers { get; }
```


