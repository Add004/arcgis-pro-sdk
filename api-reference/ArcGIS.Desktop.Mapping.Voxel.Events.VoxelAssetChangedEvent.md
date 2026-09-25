# VoxelAssetChangedEvent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.html">Voxel</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Voxel.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent.yml" sourcestartlinenumber="1">Occurs when the voxel assets of a voxel layer are changed.</p>


## Object Signature

```csharp
public sealed class VoxelAssetChangedEvent : CompositePresentationEvent<VoxelAssetEventArgs>
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent.yml" sourcestartlinenumber="1">Voxel assets include Isosurfaces, slices, sections, and locked sections. Changes can
be adds, updates, and deletes. Refer to <xref href="ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetEventArgs" data-throw-if-not-resolved="false"></xref></p>


## Members

### Subscribe(Action&lt;VoxelAssetEventArgs&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent.yml" sourcestartlinenumber="1">Subscribe to the VoxelAssetChangedEvent.</p>


```csharp
public static SubscriptionToken Subscribe(Action<VoxelAssetEventArgs> action, bool keepSubscriberAlive = false)
```
### Unsubscribe(SubscriptionToken)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent.yml" sourcestartlinenumber="1">Removes the subscriber matching the <xref href="ArcGIS.Core.Events.SubscriptionToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void Unsubscribe(SubscriptionToken token)
```
### Unsubscribe(Action&lt;VoxelAssetEventArgs&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Voxel.Events.VoxelAssetChangedEvent.yml" sourcestartlinenumber="1">Removes the first subscriber matching the provided delegate from the subscribers' list.</p>


```csharp
public static void Unsubscribe(Action<VoxelAssetEventArgs> action)
```


