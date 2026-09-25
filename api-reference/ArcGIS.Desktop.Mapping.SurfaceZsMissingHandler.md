# SurfaceZsMissingHandler

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Defines how Z values will be handled for input Geometries or their vertices that do not lie within the bounds of the input Surface.</p>


## Object Signature

```csharp
public sealed class SurfaceZsMissingHandler
```

## Remarks

<p>The default behavior for all overrides of <xref href="ArcGIS.Desktop.Mapping.Map.GetZsFromSurfaceAsync(ArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> is:</p>
<ul><li>
      <p>
     All input geometry vertex Z values are initially reset to <xref href="System.Double.NaN" data-throw-if-not-resolved="false"></xref> as a placeholder for the software when determining which Zs have yet to be successfully calculated.
     </p>
    </li><li>
      <p>
     The Z for each vertex is calculated based on its position relative to the surface.
     </p>
    </li><li>
      <p>
     After attempting to calculate the Z for all vertices, any Zs that are still NaN are considered "missing" and assigned the value of <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.OutputZ" data-throw-if-not-resolved="false"></xref>.
     </p>
    </li></ul>
<p>There may be situations where you only want to overwrite a particular subset of the input geometry vertex Z values.
     In this case you can use a combination of the OnlyProcessMissingZs and InputZ parameters
     to identify the Z values to be processed:</p>
<ul><li>
      <p>
     preset the required input geometry vertex Zs to a constant value - double.NaN can work, but there may be some other data-appropriate number.
     </p>
    </li><li>
      <p>
     set the <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.InputZ" data-throw-if-not-resolved="false"></xref> equal to the chosen constant value.
     </p>
    </li><li>
      <p>
     set the value of <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.OnlyProcessMissingZs" data-throw-if-not-resolved="false"></xref> to true.
     </p>
    </li></ul>
<p>Only those input Z’s whose value is equal to the value of InputZ (within the precision limits of the spatial reference)
     will be overwritten. Only those Zs will have a Z value calculated from the surface (or set to the value of OutputZ if they fall outside the surface extent.)</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="34"> See also:&lt;br /&gt;&lt;xref href=&quot;ArcGIS.Desktop.Mapping.Map.GetZsFromSurfaceAsync(ArcGIS.Core.Geometry.Geometry)&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;&lt;br /&gt;&lt;xref href=&quot;ArcGIS.Desktop.Mapping.Map.GetZsFromSurfaceAsync(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Desktop.Mapping.ElevationSurfaceLayer)&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;&lt;br /&gt;&lt;xref href=&quot;ArcGIS.Desktop.Mapping.Map.GetZsFromSurfaceAsync(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Desktop.Mapping.ElevationSurfaceLayer%2cArcGIS.Desktop.Mapping.SurfaceZsMissingHandler)&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;&lt;br /&gt;&lt;xref href=&quot;ArcGIS.Desktop.Mapping.Map.GetZsFromSurfaceAsync(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Desktop.Mapping.ElevationSurfaceLayer%2cArcGIS.Desktop.Mapping.SurfaceZsMissingHandler%2cSystem.Threading.CancellationToken)&quot; data-throw-if-not-resolved=&quot;false&quot;&gt;&lt;/xref&gt;&lt;br /&gt;
</code></pre>


## Members

### SurfaceZsMissingHandler()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Constructs a missing Zs handler with all properties set to the default</p>


```csharp
public SurfaceZsMissingHandler()
```
### Default

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Gets the Default SurfaceZsMissingHandler. This SurfaceZsMissingHandler is Read only.</p>


```csharp
public static SurfaceZsMissingHandler Default { get; }
```
### DefaultInputZ

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">double.NaN is the default for <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.InputZ" data-throw-if-not-resolved="false"></xref></p>


```csharp
public const double DefaultInputZ = NaN
```
### DefaultOnlyProcessMissingZs

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">false is the default for <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.OnlyProcessMissingZs" data-throw-if-not-resolved="false"></xref></p>


```csharp
public const bool DefaultOnlyProcessMissingZs = false
```
### DefaultOutputZ

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">0.0 is the default for <xref href="ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.OutputZ" data-throw-if-not-resolved="false"></xref></p>


```csharp
public const double DefaultOutputZ = 0
```
### InputZ

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Gets and sets the input geometry Z value that is considered to be missing.</p>


```csharp
public double InputZ { get; set; }
```
### OnlyProcessMissingZs

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Gets and sets, whether or not all input Z values will be processed, or only the input Z values that are determined to be missing</p>


```csharp
public bool OnlyProcessMissingZs { get; set; }
```
### OutputZ

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SurfaceZsMissingHandler.yml" sourcestartlinenumber="1">Gets and sets the output value that will replace all missing input Z values</p>


```csharp
public double OutputZ { get; set; }
```


