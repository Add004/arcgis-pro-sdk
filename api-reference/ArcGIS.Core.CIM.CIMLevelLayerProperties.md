# CIMLevelLayerProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Defines the URI and required field properties for the Indoors Level layer required for floor filtering operations.</p>


## Object Signature

```csharp
public class CIMLevelLayerProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLevelLayerProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Defines the URI and required field properties for the Indoors Level layer required for floor filtering operations.</p>


```csharp
public CIMLevelLayerProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLevelLayerProperties.</p>


```csharp
public CIMLevelLayerProperties Clone()
```
### FacilityIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the facility id (a foreign key back to the Facility feature class).</p>


```csharp
public string FacilityIDField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMLevelLayerProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMLevelLayerProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the URI for the Indoors Level layer in the map CIM.</p>


```csharp
public string LayerURI { get; set; }
```
### LevelIDField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the level id.</p>


```csharp
public string LevelIDField { get; set; }
```
### LevelNumberField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the level number.</p>


```csharp
public string LevelNumberField { get; set; }
```
### LongNameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the level &quot;long&quot; name.</p>


```csharp
public string LongNameField { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShortNameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the level &quot;short&quot; name.</p>


```csharp
public string ShortNameField { get; set; }
```
### SubLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the sublayer ID when the Level layer is a sublayer within a dynamic map service layer.</p>


```csharp
public int SubLayerID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLevelLayerProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalOrderField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field containing the vertical order for the level.</p>


```csharp
public string VerticalOrderField { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLevelLayerProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


