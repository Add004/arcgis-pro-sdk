# GroundToGridCorrection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Provides helper and extension methods for accessing and setting ground to grid corrections.</p>


## Object Signature

```csharp
public static class GroundToGridCorrection
```


## Members

### CombinedScaleFactorForSketch

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the combined scale factor when sketching within the currently active map.</p>


```csharp
public static double CombinedScaleFactorForSketch { get; }
```
### ComputeCombinedScaleFactor(Map, double, double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Compute the combined scale factor using two points and using a z elevation at the mid-point between them.</p>


```csharp
public static Task<double> ComputeCombinedScaleFactor(this Map map, double x1, double y1, double x2, double y2, double z)
```
### ConstantScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the constant scale factor used in ground to grid calculations,
when <xref href="ArcGIS.Desktop.Editing.GroundToGridCorrection.ScaleType" data-throw-if-not-resolved="false"></xref> equals <xref href="ArcGIS.Core.CIM.GroundToGridScaleType.ConstantFactor" data-throw-if-not-resolved="false"></xref></p>


```csharp
public static double ConstantScaleFactor { get; }
```
### CreateCopy(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Creates a copy of a <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection" data-throw-if-not-resolved="false"></xref> instance</p>


```csharp
public static CIMGroundToGridCorrection CreateCopy(this CIMGroundToGridCorrection c)
```
### DefaultConstantScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the default ConstantScaleFactor - a constant equal to 1.0.</p>


```csharp
public static double DefaultConstantScaleFactor { get; }
```
### DefaultDirectionOffset

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the default DirectionOffset - a constant equal to 0.0 decimal degrees.</p>


```csharp
public static double DefaultDirectionOffset { get; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets  the direction offset angle in degrees that is used in ground to grid calculations.</p>


```csharp
public static double Direction { get; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets if ground to grid corrections are enabled for supported tools.</p>


```csharp
public static bool Enabled { get; }
```
### GetConstantScaleFactor(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the constant scale factor to be used in ground to grid calculations.</p>


```csharp
public static double GetConstantScaleFactor(this CIMGroundToGridCorrection c)
```
### GetDirectionOffset(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the angle in decimal degrees to be used in ground to grid calculations.</p>


```csharp
public static double GetDirectionOffset(this CIMGroundToGridCorrection c)
```
### GetGroundToGridCorrection(Map)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the GroundToGridCorrection for the given map.</p>


```csharp
public static Task<CIMGroundToGridCorrection> GetGroundToGridCorrection(this Map map)
```
### IsCorrecting(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets whether the ground to grid correction is turned on or off.</p>


```csharp
public static bool IsCorrecting(this CIMGroundToGridCorrection c)
```
### IsEqual(CIMGroundToGridCorrection, CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Determines if two instances of <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection" data-throw-if-not-resolved="false"></xref> are equal.</p>


```csharp
public static bool IsEqual(this CIMGroundToGridCorrection c, CIMGroundToGridCorrection other)
```
### IsEqual(CIMGroundToGridCorrection, CIMGroundToGridCorrection, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Determines if two instances of <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection" data-throw-if-not-resolved="false"></xref> are equal.</p>


```csharp
public static bool IsEqual(this CIMGroundToGridCorrection c, CIMGroundToGridCorrection other, bool compareNullAsDefault)
```
### ScaleType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets the type of scale that is used in ground to grid calculations.</p>


```csharp
public static GroundToGridScaleType ScaleType { get; }
```
### SetGroundToGridCorrection(Map, CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Sets the GroundToGridCorrection for the given map.</p>


```csharp
public static Task<bool> SetGroundToGridCorrection(this Map map, CIMGroundToGridCorrection correction)
```
### UseDirection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets if the direction offset will be used when ground to grid corrections apply within the currently active map.</p>


```csharp
public static bool UseDirection { get; }
```
### UseScale

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets if the distance scale will be used when ground to grid corrections apply within the currently active map.</p>


```csharp
public static bool UseScale { get; }
```
### UsingConstantScaleFactor(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets whether a constant scale factor will be used in the ground to grid correction.</p>


```csharp
public static bool UsingConstantScaleFactor(this CIMGroundToGridCorrection c)
```
### UsingDirectionOffset(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets whether the direction offset will be used in the ground to grid correction.</p>


```csharp
public static bool UsingDirectionOffset(this CIMGroundToGridCorrection c)
```
### UsingDistanceFactor(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets whether a distance factor will be used in the ground to grid correction.</p>


```csharp
public static bool UsingDistanceFactor(this CIMGroundToGridCorrection c)
```
### UsingElevationMode(CIMGroundToGridCorrection)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.GroundToGridCorrection.yml" sourcestartlinenumber="1">Gets whether a combined scale factor will be used in the ground to grid correction.</p>


```csharp
public static bool UsingElevationMode(this CIMGroundToGridCorrection c)
```


