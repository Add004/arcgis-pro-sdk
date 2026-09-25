# CIMFacilityLayerProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Defines the URI and required field properties for the Indoors Facility layer required for floor filtering operations.</p>


## Object Signature

```csharp
public class CIMFacilityLayerProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFacilityLayerProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Defines the URI and required field properties for the Indoors Facility layer required for floor filtering operations.</p>


```csharp
public CIMFacilityLayerProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFacilityLayerProperties.</p>


```csharp
public CIMFacilityLayerProperties Clone()
```
### FacilityIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the facility id.</p>


```csharp
public string FacilityIDField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMFacilityLayerProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMFacilityLayerProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the URI for the Indoors Facility layer in the map CIM.</p>


```csharp
public string LayerURI { get; set; }
```
### NameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the facility name.</p>


```csharp
public string NameField { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SiteIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the site id (a foreign key back to the Site feature class).</p>


```csharp
public string SiteIDField { get; set; }
```
### SubLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the sublayer ID when the Facility layer is a sublayer within a dynamic map service layer.</p>


```csharp
public int SubLayerID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFacilityLayerProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFacilityLayerProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


