# BuildingRenderingFiltersChangedEventsArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BuildingRenderingFiltersChangedEventsArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.BuildingRenderingFiltersChangedEvents" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class BuildingRenderingFiltersChangedEventsArgs : EventArgs
```


## Members

### Layer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BuildingRenderingFiltersChangedEventsArgs.yml" sourcestartlinenumber="1">Gets the layer whose filter(s) changed.</p>


```csharp
public Layer Layer { get; }
```
### UpdatedObject3DRenderingFilters

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.BuildingRenderingFiltersChangedEventsArgs.yml" sourcestartlinenumber="1">Gets the collection of updated rendering filters.</p>


```csharp
public IList<CIMObject3DRenderingFilter> UpdatedObject3DRenderingFilters { get; }
```


