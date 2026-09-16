# MapMemberPropertiesChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberPropertiesChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapMemberPropertiesChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class MapMemberPropertiesChangedEventArgs : EventArgs
```


## Members

### EventHints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberPropertiesChangedEventArgs.yml" sourcestartlinenumber="1">Gets the list of properties that are modified.
The MapMemberEventHint enumerable and the MapMember enumerable have a one to one mapping.</p>


```csharp
public IList<MapMemberEventHint> EventHints { get; }
```
### MapMembers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberPropertiesChangedEventArgs.yml" sourcestartlinenumber="1">Gets the list of map members whose properties are modified.
The MapMemberEventHint enumerable and the MapMember enumerable have a one to one mapping.</p>


```csharp
public IList<MapMember> MapMembers { get; }
```


