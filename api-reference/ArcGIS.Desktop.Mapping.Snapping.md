# Snapping

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Provides access to the snapping environment within a Map.</p>


## Object Signature

```csharp
public sealed class Snapping
```

## Remarks

<p>Changing the <xref href="ArcGIS.Desktop.Mapping.Snapping.IsEnabled" data-throw-if-not-resolved="false"></xref> property has immediate effect, and saved into user preferences, and applies to both Maps and Layouts.</p>
<p>Changing the snapping modes, via <xref href="ArcGIS.Desktop.Mapping.Snapping.SetSnapMode(ArcGIS.Desktop.Mapping.SnapMode%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Mapping.Snapping.SetSnapModes(System.Collections.Generic.IEnumerable%7bArcGIS.Desktop.Mapping.SnapMode%7d)" data-throw-if-not-resolved="false"></xref> also has immediate effect, applied to all project <xref href="ArcGIS.Desktop.Mapping.MapView" data-throw-if-not-resolved="false"></xref>s, and saved into user
    preferences.</p>
<p>
    You can obtain a copy of the <xref href="ArcGIS.Desktop.Mapping.SnappingOptions" data-throw-if-not-resolved="false"></xref> for a particular <xref href="ArcGIS.Desktop.Mapping.Map" data-throw-if-not-resolved="false"></xref> using <xref href="ArcGIS.Desktop.Mapping.Snapping.GetOptions(ArcGIS.Desktop.Mapping.Map)" data-throw-if-not-resolved="false"></xref>. Changes made to 
    the resulting <xref href="ArcGIS.Desktop.Mapping.SnappingOptions" data-throw-if-not-resolved="false"></xref> object, are not immediately made to the system until the copy is committed to the project using <xref href="ArcGIS.Desktop.Mapping.Snapping.SetOptions(ArcGIS.Desktop.Mapping.Map%2cArcGIS.Desktop.Mapping.SnappingOptions)" data-throw-if-not-resolved="false"></xref>.
    </p>


## Members

### GetLayerSnapModes(Layer)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.LayerSnapModes" data-throw-if-not-resolved="false"></xref> for the specified layer.</p>


```csharp
public static LayerSnapModes GetLayerSnapModes(Layer layer)
```
### GetLayerSnapModes(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.LayerSnapModes" data-throw-if-not-resolved="false"></xref> for all layers in a Map.</p>


```csharp
public static Dictionary<Layer, LayerSnapModes> GetLayerSnapModes(Map map)
```
### GetLayerSnapModes(IEnumerable&lt;Layer&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.LayerSnapModes" data-throw-if-not-resolved="false"></xref> for a collection of Layers.</p>


```csharp
public static Dictionary<Layer, LayerSnapModes> GetLayerSnapModes(IEnumerable<Layer> layers)
```
### GetOptions(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets the snapping options for the specified map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static SnappingOptions GetOptions(Map map)
```
### GetSnapMode(SnapMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets the state of a single <xref href="ArcGIS.Desktop.Mapping.SnapMode?text=SnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static bool GetSnapMode(SnapMode mode)
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets or sets if snapping is available within the project.</p>


```csharp
public static bool IsEnabled { get; set; }
```
### SetLayerSnapModes(Layer, LayerSnapModes)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets the snap modes for a layer.</p>


```csharp
public static void SetLayerSnapModes(Layer layer, LayerSnapModes modes)
```
### SetLayerSnapModes(Layer, SnapMode, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets the state of a single SnapMode for a Layer.</p>


```csharp
public static void SetLayerSnapModes(Layer layer, SnapMode snapMode, bool isSet)
```
### SetLayerSnapModes(Layer, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets all snap modes on a layer to on(true) or off(false).</p>


```csharp
public static void SetLayerSnapModes(Layer layer, bool setAll)
```
### SetLayerSnapModes(IDictionary&lt;Layer, LayerSnapModes&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets the snap modes for a layer</p>


```csharp
public static void SetLayerSnapModes(IDictionary<Layer, LayerSnapModes> dictionary, bool resetOtherLayers = false)
```
### SetLayerSnapModes(IEnumerable&lt;Layer&gt;, LayerSnapModes)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets the snap modes for a collection of layers.</p>


```csharp
public static void SetLayerSnapModes(IEnumerable<Layer> layers, LayerSnapModes modes)
```
### SetLayerSnapModes(IEnumerable&lt;Layer&gt;, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets all snap modes on a collection of layers to on (true) or off (false).</p>


```csharp
public static void SetLayerSnapModes(IEnumerable<Layer> layers, bool setAll)
```
### SetOptions(Map, SnappingOptions)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Sets the snapping options for the specified map. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static void SetOptions(Map map, SnappingOptions options)
```
### SetSnapMode(SnapMode, bool)

- Kind: method

<p>Sets the state of a single <xref href="ArcGIS.Desktop.Mapping.SnapMode?text=SnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void SetSnapMode(SnapMode mode, bool value)
```
### SetSnapModes(IEnumerable&lt;SnapMode&gt;)

- Kind: method

<p>Sets the given snapping modes.</p>


```csharp
public static void SetSnapModes(IEnumerable<SnapMode> modes)
```
### SnapChipEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets or sets if displaying a snap chip is enabled within the project.</p>


```csharp
public static bool SnapChipEnabled { get; set; }
```
### SnapModes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Snapping.yml" sourcestartlinenumber="1">Gets or sets a collection of the current <xref href="ArcGIS.Desktop.Mapping.SnapMode?text=snapping+modes" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static List<SnapMode> SnapModes { get; set; }
```


