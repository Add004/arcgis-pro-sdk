# SnappingOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Snapping options for a map.</p>


## Object Signature

```csharp
public sealed class SnappingOptions
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">The properties for this class represent the options on the snapping options dialog.</p>


## Members

### SnappingOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Default constructor, no special settings</p>


```csharp
public SnappingOptions()
```
### SnappingOptions(SnappingOptions)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Copy constructor, initialized from another SnappingOptions</p>


```csharp
public SnappingOptions(SnappingOptions other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Snapping options for a map.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Snapping options for a map.</p>


```csharp
public override int GetHashCode()
```
### IsSnapToSketchEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the ability to snap to the sketch.</p>


```csharp
public bool IsSnapToSketchEnabled { get; set; }
```
### IsZSnappingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether Z snapping is enabled.</p>


```csharp
public bool IsZSnappingEnabled { get; set; }
```
### IsZToleranceEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the ability to use a ZTolerance.</p>


```csharp
public bool IsZToleranceEnabled { get; set; }
```
### SnapTipColor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the snap tip color.</p>


```csharp
public CIMColor SnapTipColor { get; set; }
```
### SnapTipDisplayParts

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the snap tip is fully or partially visible.</p>


```csharp
public int SnapTipDisplayParts { get; set; }
```
### XYTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the XYTolerance.</p>


```csharp
public double XYTolerance { get; set; }
```
### XYToleranceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the unit for <xref href="ArcGIS.Desktop.Mapping.SnappingOptions.XYTolerance?text=XYTolerance" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SnapXYToleranceUnit XYToleranceUnit { get; set; }
```
### ZTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SnappingOptions.yml" sourcestartlinenumber="1">Gets or sets the ZTolerance.</p>


```csharp
public double ZTolerance { get; set; }
```


