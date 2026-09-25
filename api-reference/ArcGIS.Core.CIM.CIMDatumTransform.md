# CIMDatumTransform

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Represents a datum transform.</p>


## Object Signature

```csharp
public class CIMDatumTransform : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDatumTransform()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Represents a datum transform.</p>


```csharp
public CIMDatumTransform()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDatumTransform.</p>


```csharp
public CIMDatumTransform Clone()
```
### Forward

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a forward transformation.</p>


```csharp
public bool Forward { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Reconstructs the CIMDatumTransform with a specified state from a JSON encoding.</p>


```csharp
public static CIMDatumTransform FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeoTransformation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Gets or sets the transformation.</p>


```csharp
public DatumTransformation GeoTransformation { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDatumTransform and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDatumTransform.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


