# CIMMapFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Represents a map frame on a page layout.</p>


## Object Signature

```csharp
public class CIMMapFrame : CIMFrameElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Represents a map frame on a page layout.</p>


```csharp
public CIMMapFrame()
```
### AutoCamera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the camera associated with the map frame.</p>


```csharp
public CIMAutoCamera AutoCamera { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapFrame.</p>


```csharp
public CIMMapFrame Clone()
```
### ExtentIndicators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the extent indicators associated with the map frame.</p>


```csharp
public CIMExtentIndicator[] ExtentIndicators { get; set; }
```
### ExtentIndicatorsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the map frame extent indicators are expanded in the contents pane.</p>


```csharp
public bool ExtentIndicatorsExpanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMMapFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### Grids

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the Grids and Graticules associated with the MapFrame.</p>


```csharp
public CIMMapGrid[] Grids { get; set; }
```
### LayerVisibilityOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the array of layer visibility overrides.</p>


```csharp
public CIMLayerOverrideSet[] LayerVisibilityOverrides { get; set; }
```
### MapGridsExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the map frame grids are expanded in the contents pane.</p>


```csharp
public bool MapGridsExpanded { get; set; }
```
### OverrideLayerVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether LayerVisibilityOverrides are used to override layer visibility.</p>


```csharp
public bool OverrideLayerVisibility { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the path to the map in the project.</p>


```csharp
public string URI { get; set; }
```
### UseMapBackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the MapFrame should use the Map background color.</p>


```csharp
public bool UseMapBackgroundColor { get; set; }
```
### View

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Gets or sets the view associated with the map frame.</p>


```csharp
public CIMMapView View { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


