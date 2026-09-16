# MapMemberTimeZoneChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberTimeZoneChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapMemberTimeZoneChangedEventArgs" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class MapMemberTimeZoneChangedEventArgs : EventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberTimeZoneChangedEventArgs.yml" sourcestartlinenumber="1">Use <xref href="ArcGIS.Desktop.Mapping.TimeZoneConversion.GetFieldTimeZone(ArcGIS.Desktop.Mapping.MapMember%2cSystem.String)" data-throw-if-not-resolved="false"></xref> to get the time zones.</p>


## Members

### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapMemberTimeZoneChangedEventArgs.yml" sourcestartlinenumber="1">Gets the affected map member.</p>


```csharp
public MapMember MapMember { get; }
```


