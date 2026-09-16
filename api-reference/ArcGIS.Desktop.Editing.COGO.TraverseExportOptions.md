# TraverseExportOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.COGO.html">COGO</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">Class for representing the options used in exporting a traverse.  See <xref href="ArcGIS.Desktop.Editing.COGO.Traverse.ExportAsync(ArcGIS.Desktop.Editing.COGO.TraverseExportOptions)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TraverseExportOptions
```


## Members

### TraverseExportOptions(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">Constructor for the traverse export options.</p>


```csharp
public TraverseExportOptions(string outputFileName)
```
### TraverseExportOptions(string, DirectionType, DirectionUnits, int, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">Constructor for the traverse export options.</p>


```csharp
public TraverseExportOptions(string outputFileName, DirectionType directionType, DirectionUnits directionUnits, int directionDecimalPlaces, int distanceDecimalPlaces)
```
### DirectionDecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">The number of decimal places to write directions.  Default is 0.</p>


```csharp
public int DirectionDecimalPlaces { get; set; }
```
### DirectionType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">The direction type. All directions will be output in this format.  Default is <xref href="ArcGIS.Core.CIM.DirectionType.QuadrantBearing" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DirectionType DirectionType { get; set; }
```
### DirectionUnits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">The direction units. All directions will be output in this unit.  Default is <xref href="ArcGIS.Core.CIM.DirectionUnits.DegreesMinutesSeconds" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DirectionUnits DirectionUnits { get; set; }
```
### DistanceDecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">The number of decimal places to write distances.  Default is 3</p>


```csharp
public int DistanceDecimalPlaces { get; set; }
```
### OutputFileName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.COGO.TraverseExportOptions.yml" sourcestartlinenumber="1">The path and name of the output file.  If this file already exists it will be overwritten.</p>


```csharp
public string OutputFileName { get; set; }
```


