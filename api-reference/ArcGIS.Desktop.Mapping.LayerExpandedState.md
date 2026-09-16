# LayerExpandedState

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerExpandedState.yml" sourcestartlinenumber="1">Defines the set of values for a layer's expanded state on creation.
See <xref href="ArcGIS.Desktop.Mapping.LayerCreationParams.ExpandedState" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum LayerExpandedState
```


## Members

### Collapsed

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerExpandedState.yml" sourcestartlinenumber="1">The layer is collapsed.  if sublayers exist then they will use
the default expanded state according to layer type</p>


```csharp
Collapsed = 2
```
### Default

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerExpandedState.yml" sourcestartlinenumber="1">The expanded state of the layer is set according to the layer type.</p>


```csharp
Default = 0
```
### Expanded

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerExpandedState.yml" sourcestartlinenumber="1">The layer is expanded. If sublayers exist then they will use
the default expanded state according to layer type.</p>


```csharp
Expanded = 1
```


