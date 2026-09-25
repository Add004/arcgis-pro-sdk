# CIMFeatureExtrusion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Represents the extrusion properties of a feature layer.</p>


## Object Signature

```csharp
public class CIMFeatureExtrusion : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFeatureExtrusion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Represents the extrusion properties of a feature layer.</p>


```csharp
public CIMFeatureExtrusion()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFeatureExtrusion.</p>


```csharp
public CIMFeatureExtrusion Clone()
```
### ExtrusionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Gets or sets the extrusion expression.</p>


```csharp
public string ExtrusionExpression { get; set; }
```
### ExtrusionExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Gets or sets an Arcade expression info object for an expression that returns a numeric value.</p>


```csharp
public CIMExpressionInfo ExtrusionExpressionInfo { get; set; }
```
### ExtrusionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Gets or sets the extrusion type.</p>


```csharp
public ExtrusionType ExtrusionType { get; set; }
```
### ExtrusionUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Gets or sets the feature layer's extrusion unit.</p>


```csharp
public LinearUnit ExtrusionUnit { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Reconstructs the CIMFeatureExtrusion with a specified state from a JSON encoding.</p>


```csharp
public static CIMFeatureExtrusion FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFeatureExtrusion and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureExtrusion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


