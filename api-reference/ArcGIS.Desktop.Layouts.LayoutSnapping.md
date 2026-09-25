# LayoutSnapping

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutSnapping.yml" sourcestartlinenumber="1">Provides access to the snapping environment within a Layout.</p>


## Object Signature

```csharp
public sealed class LayoutSnapping
```

## Remarks

<p>Changing the <xref href="ArcGIS.Desktop.Layouts.LayoutSnapping.IsEnabled" data-throw-if-not-resolved="false"></xref> property has immediate effect, and saved into user preferences, and applies to both Maps and Layouts.</p>
<p>Changing the snapping modes, via <xref href="ArcGIS.Desktop.Layouts.LayoutSnapping.SetSnapMode(ArcGIS.Desktop.Layouts.LayoutSnapMode%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Layouts.LayoutSnapping.SetSnapModes(System.Collections.Generic.IEnumerable%7bArcGIS.Desktop.Layouts.LayoutSnapMode%7d)" data-throw-if-not-resolved="false"></xref> also has immediate effect, applied to all project <xref href="ArcGIS.Desktop.Layouts.LayoutView" data-throw-if-not-resolved="false"></xref>s, and saved into user
    preferences.</p>


## Members

### LayoutSnapping()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutSnapping.yml" sourcestartlinenumber="1">Provides access to the snapping environment within a Layout.</p>


```csharp
public LayoutSnapping()
```
### GetSnapMode(LayoutSnapMode)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutSnapping.yml" sourcestartlinenumber="1">Gets the state of a single <xref href="ArcGIS.Desktop.Layouts.LayoutSnapMode?text=LayoutSnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static bool GetSnapMode(LayoutSnapMode mode)
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutSnapping.yml" sourcestartlinenumber="1">Gets or sets if snapping is available within the project.</p>


```csharp
public static bool IsEnabled { get; set; }
```
### SetSnapMode(LayoutSnapMode, bool)

- Kind: method

<p>Sets the state of a single <xref href="ArcGIS.Desktop.Layouts.LayoutSnapMode?text=LayoutSnapMode" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static void SetSnapMode(LayoutSnapMode mode, bool value)
```
### SetSnapModes(IEnumerable&lt;LayoutSnapMode&gt;)

- Kind: method

<p>Sets the given snapping modes.</p>


```csharp
public static void SetSnapModes(IEnumerable<LayoutSnapMode> modes)
```
### SnapModes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.LayoutSnapping.yml" sourcestartlinenumber="1">Gets or sets a collection of the current <xref href="ArcGIS.Desktop.Layouts.LayoutSnapMode?text=snapping+modes" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static List<LayoutSnapMode> SnapModes { get; set; }
```


