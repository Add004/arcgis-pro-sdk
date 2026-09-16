# CIMS52TextGroupVisibilitySettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Represents S-52 text group settings.</p>


## Object Signature

```csharp
public class CIMS52TextGroupVisibilitySettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMS52TextGroupVisibilitySettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Represents S-52 text group settings.</p>


```csharp
public CIMS52TextGroupVisibilitySettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMS52TextGroupVisibilitySettings.</p>


```csharp
public CIMS52TextGroupVisibilitySettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Reconstructs the CIMS52TextGroupVisibilitySettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMS52TextGroupVisibilitySettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowBerthNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;berth number&quot; text group should be visible.</p>


```csharp
public bool ShowBerthNumber { get; set; }
```
### ShowCurrentVelocity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;current velocity&quot; text group should be visible.</p>


```csharp
public bool ShowCurrentVelocity { get; set; }
```
### ShowGeographicNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;geographic names&quot; text group should be visible.</p>


```csharp
public bool ShowGeographicNames { get; set; }
```
### ShowHeightOfIsletOrLandFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;height of islet or land feature&quot; text group should be visible.</p>


```csharp
public bool ShowHeightOfIsletOrLandFeature { get; set; }
```
### ShowImportantText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;important text&quot; text group should be visible.</p>


```csharp
public bool ShowImportantText { get; set; }
```
### ShowLightDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;light descriptions&quot; text group should be visible.</p>


```csharp
public bool ShowLightDescription { get; set; }
```
### ShowMagneticVariationAndSweptDepth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;magnetic variation and swept depth&quot; text group should be visible.</p>


```csharp
public bool ShowMagneticVariationAndSweptDepth { get; set; }
```
### ShowNamesForPositionReporting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;names for position reporting&quot; text group should be visible.</p>


```csharp
public bool ShowNamesForPositionReporting { get; set; }
```
### ShowNatureOfSeabed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;nature of seabed&quot; text group should be visible.</p>


```csharp
public bool ShowNatureOfSeabed { get; set; }
```
### ShowNoteOnChartData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the &quot;note on chart data&quot; text group should be visible.</p>


```csharp
public bool ShowNoteOnChartData { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMS52TextGroupVisibilitySettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52TextGroupVisibilitySettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


