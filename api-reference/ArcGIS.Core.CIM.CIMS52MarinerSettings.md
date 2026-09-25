# CIMS52MarinerSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Represents S-52 mariner settings object for controlling the drawing of ENC layers.</p>


## Object Signature

```csharp
public class CIMS52MarinerSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMS52MarinerSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Represents S-52 mariner settings object for controlling the drawing of ENC layers.</p>


```csharp
public CIMS52MarinerSettings()
```
### AreaSymbolizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the area symbolization type. This controls the line symbol style for area boundaries.</p>


```csharp
public S52AreaSymbolizationType AreaSymbolizationType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMS52MarinerSettings.</p>


```csharp
public CIMS52MarinerSettings Clone()
```
### ColorScheme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the color scheme.</p>


```csharp
public S52ColorScheme ColorScheme { get; set; }
```
### DeepContour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the deep water contour depth in meters.</p>


```csharp
public double DeepContour { get; set; }
```
### DepthDisplayUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the depth units (meters/feet/fathoms) for display.</p>


```csharp
public S52DepthDisplayUnits DepthDisplayUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMS52MarinerSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMS52MarinerSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### HonorSCAMIN

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the 'SCAMIN' (scale min) S-57 feature attribute will be used.</p>


```csharp
public bool HonorSCAMIN { get; set; }
```
### LabelContours

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the depth contour labels, including safety contour labels.</p>


```csharp
public bool LabelContours { get; set; }
```
### LabelSafetyContours

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the safety contour labels.</p>


```csharp
public bool LabelSafetyContours { get; set; }
```
### PointSymbolizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the S-52 point feature symbolization type (simplified/paperchart).</p>


```csharp
public S52PointSymbolizationType PointSymbolizationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SafetyContour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the depth of the safety contour in meters.</p>


```csharp
public double SafetyContour { get; set; }
```
### ShallowContour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets the depth of the shallow contour in meters.</p>


```csharp
public double ShallowContour { get; set; }
```
### ShowDataQuality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display data quality (M_QUAL) for S-57 features.</p>


```csharp
public bool ShowDataQuality { get; set; }
```
### ShowDisplayBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the S-52 &quot;displaybase&quot; display category is enabled.</p>


```csharp
public bool ShowDisplayBase { get; set; }
```
### ShowIsolatedDangers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display isolated dangers in shallow water.</p>


```csharp
public bool ShowIsolatedDangers { get; set; }
```
### ShowLowAccuracy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use low accuracy symbols (CATZOC).</p>


```csharp
public bool ShowLowAccuracy { get; set; }
```
### ShowNOBJNM

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the national name attribute on S-57 features.</p>


```csharp
public bool ShowNOBJNM { get; set; }
```
### ShowOtherDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the S-52 &quot;other&quot; display category is enabled.</p>


```csharp
public bool ShowOtherDisplay { get; set; }
```
### ShowShallowDepthPattern

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the shallow depth pattern will be symbolized.</p>


```csharp
public bool ShowShallowDepthPattern { get; set; }
```
### ShowStandardDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the S-52 &quot;standard&quot; display category is enabled.</p>


```csharp
public bool ShowStandardDisplay { get; set; }
```
### ShowTwoDepthShades

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether two or four depth shades will be used; two is the default.</p>


```csharp
public bool ShowTwoDepthShades { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMS52MarinerSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52MarinerSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


