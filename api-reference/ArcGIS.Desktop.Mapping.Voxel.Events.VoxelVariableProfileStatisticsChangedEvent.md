# VoxelVariableProfileStatisticsChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelVariableProfileStatisticsChangedEvent.yml" sourcestartlinenumber="1">Occurs when the statistics for an underlying voxel variable have been updated.</p>


## Object Signature

```csharp
public sealed class VoxelVariableProfileStatisticsChangedEvent : CompositePresentationEvent<VoxelVariableProfileEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelVariableProfileStatisticsChangedEvent.yml" sourcestartlinenumber="1">When a voxel variable profile is first loaded, its voxel data values must be read and
statistics computed.</p>


## Members

### Subscribe(Action&lt;VoxelVariableProfileEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelVariableProfileStatisticsChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the VoxelVariableProfileStatisticsChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<VoxelVariableProfileEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelVariableProfileStatisticsChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;VoxelVariableProfileEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelVariableProfileStatisticsChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<VoxelVariableProfileEventArgs> action)
```


