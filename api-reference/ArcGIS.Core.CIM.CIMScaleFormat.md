# CIMScaleFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Represents the scale formatting options.</p>


## Object Signature

```csharp
public class CIMScaleFormat : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMScaleFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Represents the scale formatting options.</p>


```csharp
public CIMScaleFormat()
```
### AbbreviateUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to abbreviate the units in the scale string.</p>


```csharp
public bool AbbreviateUnits { get; set; }
```
### CapitalizeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to capitalize the units in the scale string.</p>


```csharp
public bool CapitalizeUnits { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMScaleFormat.</p>


```csharp
public CIMScaleFormat Clone()
```
### DecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the number decimal places.</p>


```csharp
public int DecimalPlaces { get; set; }
```
### DecimalPlacesThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the number the scale has to be less than or equal to display decimal places.</p>


```csharp
public double DecimalPlacesThreshold { get; set; }
```
### EqualsSign

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the text used for 'equals', e.g, '=' in 1 inch=5 miles.</p>


```csharp
public string EqualsSign { get; set; }
```
### FormatType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the format used to display scale, i.e., 1:20000 or 1 inch equals 5 miles.</p>


```csharp
public ScaleFormatType FormatType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMScaleFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMScaleFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the map units used to display a scale, e.g, the 'miles' in 1 inch=5 miles.</p>


```csharp
public LinearUnit MapUnits { get; set; }
```
### PageUnitValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the number preceding the page units in a scale, i.e., the '1' in 1 inch=5 miles.</p>


```csharp
public double PageUnitValue { get; set; }
```
### PageUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the page units used to display a scale,e.g, the 'inch' in 1 inch=5 miles.</p>


```csharp
public LinearUnit PageUnits { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReverseOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to reverse the standard order. e.g. [1:1000] becomes [1000:1] and [1 in=10 mi] becomes [10 mi=1 in].</p>


```csharp
public bool ReverseOrder { get; set; }
```
### Separator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets the character(s) used to separate '1' from the scale in an absolute scale, e.g ':' in 1:20000.</p>


```csharp
public string Separator { get; set; }
```
### ShowThousandSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the thousands separator, e.g., 1:20,000.</p>


```csharp
public bool ShowThousandSeparator { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMScaleFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


