# MapSelectionChangedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class MapSelectionChangedEventArgs
```


## Members

### MapSelectionChangedEventArgs(Map, SelectionSet, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEventArgs.yml" sourcestartlinenumber="1">Constructs a new MapSelectionChangedEventArgs.</p>


```csharp
public MapSelectionChangedEventArgs(Map map, SelectionSet selection, bool isPointSelection)
```
### IsPointSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets if the selection was based on a point and click as opposed to a click and drag selection.</p>


```csharp
public bool IsPointSelection { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the map for which the selection changed.</p>


```csharp
public Map Map { get; }
```
### Selection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapSelectionChangedEventArgs.yml" sourcestartlinenumber="1">Gets the selection.</p>


```csharp
public SelectionSet Selection { get; }
```


