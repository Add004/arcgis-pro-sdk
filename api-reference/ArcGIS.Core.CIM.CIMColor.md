# CIMColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Supports colors in the CIM model by providing low level access to properties common amongst all color types.</p>


## Object Signature

```csharp
public abstract class CIMColor : CIMObject, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">This is the base color type which provides access to the color values and color space. Alpha is always the last value in the value array.</p>


## Members

### CIMColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Supports colors in the CIM model by providing low level access to properties common amongst all color types.</p>


```csharp
protected CIMColor()
```
### Alpha

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets and sets alpha.</p>


```csharp
public float Alpha { get; set; }
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array. Not implemented on CIMColor.</p>


```csharp
protected virtual short AlphaIndex()
```
### AreEqual(CIMColor, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Determines if two <xref href="ArcGIS.Core.CIM.CIMColor" data-throw-if-not-resolved="false"></xref> are equal.</p>


```csharp
public static bool AreEqual(CIMColor color1, CIMColor color2)
```
### ColorSpace

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets or sets the color space of the color.
This color space is defined by an ICC color profile (except for spot colors which use a dedicated color space definition).</p>


```csharp
public CIMColorSpace ColorSpace { get; set; }
```
### CreateCMYKColor(double, double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new CMYK color from input parameters.</p>


```csharp
public static CIMColor CreateCMYKColor(double c = 0, double m = 0, double y = 0, double k = 50, double alpha = 100)
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Not implemented on CIMColor.</p>


```csharp
protected virtual void CreateDefaultValues()
```
### CreateGrayColor(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new gray color from input parameters.</p>


```csharp
public static CIMColor CreateGrayColor(double l, double alpha = 100)
```
### CreateHSLColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new HSL color from input parameters.</p>


```csharp
public static CIMColor CreateHSLColor(double h, double s, double l, double alpha = 100)
```
### CreateHSVColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new HSV color from input parameters.</p>


```csharp
public static CIMColor CreateHSVColor(double h, double s, double v, double alpha = 100)
```
### CreateLABColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new RGB color from input parameters.</p>


```csharp
public static CIMColor CreateLABColor(double l, double a, double b, double alpha = 100)
```
### CreateRGBColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a new RGB color from input parameters.</p>


```csharp
public static CIMColor CreateRGBColor(double r, double g, double b, double alpha = 100)
```
### CreateSpotColor(string, CIMSpotColorSpace, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a Spot color from input parameters.</p>


```csharp
public static CIMColor CreateSpotColor(string name, CIMSpotColorSpace colorSpace, double tint, double alpha = 100)
```
### CreateXYZColor(double, double, double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates an new XYZ color from input parameters.</p>


```csharp
public static CIMColor CreateXYZColor(double x, double y, double z, double alpha = 100)
```
### Equals(CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.CIM.CIMColor" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public bool Equals(CIMColor other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Determines whether two <xref href="ArcGIS.Core.CIM.CIMColor" data-throw-if-not-resolved="false"></xref> instances are equal.</p>


```csharp
public override bool Equals(object other)
```
### GetAlphaValue()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets the alpha value of the color.</p>


```csharp
public double GetAlphaValue()
```
### GetColorComponent(long)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets the color component at the specified index.</p>


```csharp
public double GetColorComponent(long index)
```
### GetColorObject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a color object from an XML string.</p>


```csharp
public static CIMColor GetColorObject(string colorObjectXml)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets a hash code for the current object.</p>


```csharp
public override int GetHashCode()
```
### NoColor()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Creates a fully transparent color.</p>


```csharp
public static CIMColor NoColor()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SetAlphaValue(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Sets the alpha value on the color.</p>


```csharp
public void SetAlphaValue(double val)
```
### SetColorComponent(long, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Sets the color component at the specified index.</p>


```csharp
public void SetColorComponent(long index, double value)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Gets or sets the values for the color and alpha channels as defined by the color model. Alpha is the last value in the array for all colors.</p>


```csharp
public double[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### operator ==(CIMColor, CIMColor)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">color1</code> and <code class="paramref">color2</code> are equal.</p>


```csharp
public static bool operator ==(CIMColor color1, CIMColor color2)
```
### operator !=(CIMColor, CIMColor)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">color1</code> and <code class="paramref">color2</code> are not equal.</p>


```csharp
public static bool operator !=(CIMColor color1, CIMColor color2)
```
### sDefaultAlpha

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.CIMColor.yml" sourcestartlinenumber="1">Default alpha value for colors.</p>


```csharp
protected static double sDefaultAlpha
```


