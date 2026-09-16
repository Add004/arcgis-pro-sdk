# IColorFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll


## Object Signature

```csharp
public interface IColorFactory
```


## Members

### BlackRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the black color.</p>


```csharp
CIMColor BlackRGB { get; }
```
### BlueRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the blue color.</p>


```csharp
CIMColor BlueRGB { get; }
```
### ConstructColorRamp(ColorRampAlgorithm)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Construct a color ramp using the specified algorithm. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMColorRamp ConstructColorRamp(ColorRampAlgorithm algorithm)
```
### ConstructColorRamp(ColorRampAlgorithm, CIMColor, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Construct a color ramp using the specified algorithm. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMColorRamp ConstructColorRamp(ColorRampAlgorithm algorithm, CIMColor fromColor, CIMColor toColor)
```
### ConvertToColorSpace(CIMColor, CIMColorSpaceType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Convert the specified CIMColor to the provided color space. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMColor ConvertToColorSpace(CIMColor color, CIMColorSpaceType colorSpace)
```
### ConvertToHSV(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Convert the CIMColor color to CIMHSVColor. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMHSVColor ConvertToHSV(CIMColor color)
```
### ConvertToRGB(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Convert the input CIMColor to CIMRGBColor. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMRGBColor ConvertToRGB(CIMColor color)
```
### CreateColor(Color)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Creates the specified color.</p>


```csharp
CIMColor CreateColor(Color color)
```
### CreateColor(Color)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Creates the specified color.</p>


```csharp
CIMColor CreateColor(Color color)
```
### CreateRGBColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Creates the specified color.</p>


```csharp
CIMColor CreateRGBColor(double R, double G, double B, double A = 100)
```
### GenerateColorsFromColorRamp(CIMColorRamp, int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Generate a list of [count] colors from the specified color ramp. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
List<CIMColor> GenerateColorsFromColorRamp(CIMColorRamp colorRamp, int count)
```
### GetColorRamp(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the color ramp of the specified name. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
CIMColorRamp GetColorRamp(string colorRampName)
```
### GetColorRampCategories()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the list of color ramp categories. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IReadOnlyList<string> GetColorRampCategories()
```
### GetColorRampNames(IEnumerable&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the list of color ramp names for a set of categories. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IReadOnlyList<string> GetColorRampNames(IEnumerable<string> categories)
```
### GetColorRampNames(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the list of color ramp names for a specific category. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
IReadOnlyList<string> GetColorRampNames(string category)
```
### GreenRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the freen color.</p>


```csharp
CIMColor GreenRGB { get; }
```
### GreyRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the grey color.</p>


```csharp
CIMColor GreyRGB { get; }
```
### RedRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the red color.</p>


```csharp
CIMColor RedRGB { get; }
```
### ReverseColorRamp(CIMColorRamp)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Reverses the color ramp.</p>


```csharp
CIMColorRamp ReverseColorRamp(CIMColorRamp colorRamp)
```
### WhiteRGB

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.IColorFactory.yml" sourcestartlinenumber="1">Gets the white color.</p>


```csharp
CIMColor WhiteRGB { get; }
```


