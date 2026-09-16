# CIMFloorFilterSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Represents floor filter settings.</p>


## Object Signature

```csharp
public class CIMFloorFilterSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloorFilterSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Represents floor filter settings.</p>


```csharp
public CIMFloorFilterSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloorFilterSettings.</p>


```csharp
public CIMFloorFilterSettings Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the floor filter is enabled and filtering the displayed content according to the floor filter selections.</p>


```csharp
public bool Enabled { get; set; }
```
### FloorVisibilityMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the visibility mode for 3D floor aware scenes, which is used when deciding how to display 3D floor aware layers.</p>


```csharp
public FloorVisibilityMode FloorVisibilityMode { get; set; }
```
### FocusSelectedFacility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the floor filter should display only the selected facility or all facilities.</p>


```csharp
public bool FocusSelectedFacility { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMFloorFilterSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloorFilterSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### LongNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the levels lists are showing the long names from the NAME field or showing the short names from the NAME_SHORT field.</p>


```csharp
public bool LongNames { get; set; }
```
### Minimized

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the floor filter has been minimized to show only the levels list or if it is showing the full set of breadcrumbs.</p>


```csharp
public bool Minimized { get; set; }
```
### PinnedLevels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the levels portion of the floor filter have been pinned to show the levels lists or the floor filter includes the levels as a breadcrumb dropdown.</p>


```csharp
public bool PinnedLevels { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectedFacilityID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the facility ID for the selected facility, which is used when filtering layers by FACILITY_ID.</p>


```csharp
public string SelectedFacilityID { get; set; }
```
### SelectedLevelID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the level ID for the selected level, which is used when filtering layers by LEVEL_ID or the layer's configured floor-aware properties.</p>


```csharp
public string SelectedLevelID { get; set; }
```
### SelectedSiteID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the site ID for the selected site, which is used when filtering layers by SITE_ID (optional).</p>


```csharp
public string SelectedSiteID { get; set; }
```
### SelectedVerticalOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the vertical order which is used when filtering layers by VERTICAL_ORDER or the layer's configured floor-aware properties.</p>


```csharp
public int SelectedVerticalOrder { get; set; }
```
### SiteFacilityIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the array of facility ids belonging to the selected site (only if just site has been selected).</p>


```csharp
public string[] SiteFacilityIDs { get; set; }
```
### SiteLevelIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets the array of level ids belonging to the selected site (only if just site has been selected).</p>


```csharp
public string[] SiteLevelIDs { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloorFilterSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseVerticalOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the floor filter should use the selected vertical order for floor filtering.</p>


```csharp
public bool UseVerticalOrder { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorFilterSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


