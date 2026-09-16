# LasPointPipelineSelectionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Represents the pipeline filter used when selecting points in a LAS dataset layer.
The pipeline filter selects a series of points along a line based on
the original selection until the filter parameters are exceeded.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="7">See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SelectAsync(ArcGIS.Desktop.Mapping.LasPointSelectionFilter%2cArcGIS.Desktop.Mapping.SelectionCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointPipelineSelectionFilter : LasPointSelectionFilter
```


## Members

### LasPointPipelineSelectionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Create an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointPipelineSelectionFilter()
```
### ApplyWindCorrection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the flag indicating that wind correction parameters are to be applied.
The default value is false.</p>


```csharp
public bool ApplyWindCorrection { get; set; }
```
### MaximumDeviationAngle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum deviation angle in degrees. This is the maximum angle that the power line
can rotate from the center. The default value is 10 degrees.</p>


```csharp
public double MaximumDeviationAngle { get; set; }
```
### MaximumGap

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the maximum gap (in meters) allowed in the modeling. The default value is 20 meters.</p>


```csharp
public double MaximumGap { get; set; }
```
### MinimumLength

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the minimum length value in meters. This is the minimum length that
the modeling will correct for wind with power lines longer than this distance.
The default value is 20 meters.</p>


```csharp
public double MinimumLength { get; set; }
```
### Tolerance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointPipelineSelectionFilter.yml" sourcestartlinenumber="1">Gets and sets the tolerance value in meters. This is the maximum distance
in 3D that the points used to model the power line can be from one another.
The default value is 0.3048 meters.</p>


```csharp
public double Tolerance { get; set; }
```


