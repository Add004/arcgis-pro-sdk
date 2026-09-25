# MapControlEventHandler

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Provides access to input events received by map controls.</p>


## Object Signature

```csharp
public static class MapControlEventHandler
```


## Members

### OnKeyDown

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when a key is pressed while a map control has focus.</p>


```csharp
public static MapControlEventHandler.Event<MapControlKeyEventArgs> OnKeyDown { get; }
```
### OnKeyUp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when a key is released while a map control has focus.</p>


```csharp
public static MapControlEventHandler.Event<MapControlKeyEventArgs> OnKeyUp { get; }
```
### OnMouseDoubleClick

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when a mouse button is double-clicked in a map control.</p>


```csharp
public static MapControlEventHandler.Event<MapControlMouseButtonEventArgs> OnMouseDoubleClick { get; }
```
### OnMouseDown

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when a mouse button is pressed in a map control.</p>


```csharp
public static MapControlEventHandler.Event<MapControlMouseButtonEventArgs> OnMouseDown { get; }
```
### OnMouseMove

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when the mouse moves in a map control.</p>


```csharp
public static MapControlEventHandler.Event<MapControlMouseEventArgs> OnMouseMove { get; }
```
### OnMouseUp

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when a mouse button is released in a map control.</p>


```csharp
public static MapControlEventHandler.Event<MapControlMouseButtonEventArgs> OnMouseUp { get; }
```
### OnMouseWheel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.MapControlEventHandler.yml" sourcestartlinenumber="1">Gets the event that occurs when the mouse wheel is moved in a map control.</p>


```csharp
public static MapControlEventHandler.Event<MapControlMouseWheelEventArgs> OnMouseWheel { get; }
```


