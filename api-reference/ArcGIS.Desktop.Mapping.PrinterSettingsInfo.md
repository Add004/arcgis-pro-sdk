# PrinterSettingsInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Represents a PrinterSettingsInfo object that can be used to print a
<xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, or a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class PrinterSettingsInfo
```


## Members

### PrinterSettingsInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Initialize a new instance of PrinterSettingsInfo.</p>


```csharp
public PrinterSettingsInfo()
```
### DoShowSelectionSymbology

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Get or sets if the selection symbology should be shown for all the layerss.</p>


```csharp
public bool DoShowSelectionSymbology { get; set; }
```
### LayoutOrMapName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the layout or map to be printed.</p>


```csharp
public string LayoutOrMapName { get; set; }
```
### PrintAsImage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating to send an image stream rather than vector information to the printer.</p>


```csharp
public bool PrintAsImage { get; set; }
```
### PrintToFile

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Get or sets a boolean to create a printer file (.prn) that can be used later, instead of printing immediately.</p>


```csharp
public bool PrintToFile { get; set; }
```
### PrinterFileName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets the full path of the printer file.</p>


```csharp
public string PrinterFileName { get; set; }
```
### PrinterSettings

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets the <xref href="System.Drawing.Printing.PrinterSettings" data-throw-if-not-resolved="false"></xref> object that contains the settings used for printing.</p>


```csharp
public PrinterSettings PrinterSettings { get; set; }
```
### RasterSampleRatio

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets the image quality resample ratio.</p>


```csharp
public int RasterSampleRatio { get; set; }
```
### TileOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets the tiling options for how the layout should be printed when it exceeds the paper size.</p>


```csharp
public TilingOptions TileOptions { get; set; }
```
### Tiling

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Gets or sets a boolean indicating whether the layout should be tiled when printed.</p>


```csharp
public bool Tiling { get; set; }
```
### ValidatePrinterSettingsInfo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettingsInfo.yml" sourcestartlinenumber="1">Validates the PrinterSettingsInfo properties set by the user.</p>


```csharp
public void ValidatePrinterSettingsInfo()
```


