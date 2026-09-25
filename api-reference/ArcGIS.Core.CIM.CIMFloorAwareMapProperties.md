# CIMFloorAwareMapProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Defines the properties needed to identify the Indoors layers and some required fields for each layer which are used for floor filtering operations, as well as properties for the map's floor filter.</p>


## Object Signature

```csharp
public class CIMFloorAwareMapProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloorAwareMapProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Defines the properties needed to identify the Indoors layers and some required fields for each layer which are used for floor filtering operations, as well as properties for the map's floor filter.</p>


```csharp
public CIMFloorAwareMapProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloorAwareMapProperties.</p>


```csharp
public CIMFloorAwareMapProperties Clone()
```
### DefaultFloorFilterSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the default properties for the map's floor filter control. Used as default when creating new map views.</p>


```csharp
public CIMFloorFilterSettings DefaultFloorFilterSettings { get; set; }
```
### FacilityLayerProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties for the Indoors Facilities layer in the map.</p>


```csharp
public CIMFacilityLayerProperties FacilityLayerProperties { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMFloorAwareMapProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloorAwareMapProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LevelLayerProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties for the Indoors Levels layer in the map.</p>


```csharp
public CIMLevelLayerProperties LevelLayerProperties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SiteLayerProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties for the Indoors Sites layer in the map.</p>


```csharp
public CIMSiteLayerProperties SiteLayerProperties { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloorAwareMapProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareMapProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


