# CIMProfileFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Layout element used to draw Profile view of
Runway, Terrain, obstacles and Obstruction Identification Surfaces (OIS).</p>


## Object Signature

```csharp
public class CIMProfileFrame : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Layout element used to draw Profile view of
Runway, Terrain, obstacles and Obstruction Identification Surfaces (OIS).</p>


```csharp
public CIMProfileFrame()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileFrame.</p>


```csharp
public CIMProfileFrame Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### Grid

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the display options for the grid.</p>


```csharp
public CIMProfileGrid Grid { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the height of the profile, used if the height option is set to ConstantHeight.</p>


```csharp
public double Height { get; set; }
```
### HeightOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the option to control the height of profile.</p>


```csharp
public ProfileFrameHeightOption HeightOption { get; set; }
```
### HeightUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the height units of the profile, used if the height option is set to ConstantHeight.</p>


```csharp
public LinearUnit HeightUnits { get; set; }
```
### OISLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer of the OIS feature which defines the data for which profile is drawn.</p>


```csharp
public string OISLayerURI { get; set; }
```
### OISSurfaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the display option for all the OIS surfaces
shown in the profile.</p>


```csharp
public CIMProfileOIS[] OISSurfaces { get; set; }
```
### Obstacles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the display option for all the point obstacles
shown in the profile.</p>


```csharp
public CIMProfileObstacle[] Obstacles { get; set; }
```
### PrimaryOISDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the primary OIS surface for which profile is created.</p>


```csharp
public string PrimaryOISDescription { get; set; }
```
### PrimarySurfaceDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the primary surface description.</p>


```csharp
public string PrimarySurfaceDescription { get; set; }
```
### ProfileStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the style of the profile frame.</p>


```csharp
public ProfileFrameStyle ProfileStyle { get; set; }
```
### ProfileType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the option for profile type.</p>


```csharp
public ProfileFrameType ProfileType { get; set; }
```
### Ratio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the ratio between width and height scale.</p>


```csharp
public double Ratio { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Runway

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the text symbol for runway elevation.</p>


```csharp
public CIMProfileRunway Runway { get; set; }
```
### RunwayDesignator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the runway designator for which profile is created.</p>


```csharp
public string RunwayDesignator { get; set; }
```
### RunwayEndLeftAsReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use left end of runway as base elevation.</p>


```csharp
public bool RunwayEndLeftAsReference { get; set; }
```
### SecondaryOISDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets the secondary OIS description for cases where different classifications were used for the
ends of runway user can choose secondary classification.</p>


```csharp
public string SecondaryOISDescription { get; set; }
```
### Terrain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Gets or sets display options for terrain.</p>


```csharp
public CIMProfileTerrain Terrain { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


