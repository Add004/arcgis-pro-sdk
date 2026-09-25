# ColorRampLegendClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColorRampLegendClass.yml" sourcestartlinenumber="1">Represents the legend class for a color ramp.</p>


## Object Signature

```csharp
public class ColorRampLegendClass : LegendClass
```


## Members

### GetColorRamp()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColorRampLegendClass.yml" sourcestartlinenumber="1">Gets the color ramp for this legend class.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMColorRamp GetColorRamp()
```
### MaxLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColorRampLegendClass.yml" sourcestartlinenumber="1">Gets the label for the maximum value for the color ramp legend class.</p>


```csharp
public string MaxLabel { get; }
```
### MinLabel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ColorRampLegendClass.yml" sourcestartlinenumber="1">Gets the label for the minimum value for the color ramp legend class.</p>


```csharp
public string MinLabel { get; }
```


