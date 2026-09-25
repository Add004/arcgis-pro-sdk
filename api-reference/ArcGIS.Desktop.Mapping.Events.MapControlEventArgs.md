# MapControlEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventArgs.yml" sourcestartlinenumber="1">Provides data for map control input events.</p>


## Object Signature

```csharp
public class MapControlEventArgs : EventArgs
```


## Members

### Handled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventArgs.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the input event has been handled.</p>


```csharp
public bool Handled { get; set; }
```
### MapControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventArgs.yml" sourcestartlinenumber="1">Gets the map control that received the input.</p>


```csharp
public MapControl MapControl { get; }
```
### Modifiers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventArgs.yml" sourcestartlinenumber="1">Gets the modifier keys that were pressed when the input was received.</p>


```csharp
public ModifierKeys Modifiers { get; }
```


