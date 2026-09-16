# CIMMosaicRule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Represents a mosaic rule.</p>


## Object Signature

```csharp
public class CIMMosaicRule : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMosaicRule()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Represents a mosaic rule.</p>


```csharp
public CIMMosaicRule()
```
### Ascending

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the mosaic rule uses ascending order.</p>


```csharp
public bool Ascending { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMosaicRule.</p>


```csharp
public CIMMosaicRule Clone()
```
### FIDs

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets an array of IDs.</p>


```csharp
public long[] FIDs { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Reconstructs the CIMMosaicRule with a specified state from a JSON encoding.</p>


```csharp
public static CIMMosaicRule FromJson(string json, JsonDeserializationSettings settings = null)
```
### LockRasterID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the ID of the lock raster.</p>


```csharp
public string LockRasterID { get; set; }
```
### MosaicMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the mosaic method.</p>


```csharp
public RasterMosaicMethod MosaicMethod { get; set; }
```
### MosaicOperatorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the mosaic operator type.</p>


```csharp
public RasterMosaicOperatorType MosaicOperatorType { get; set; }
```
### OrderByBaseValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the order by base value.</p>


```csharp
public object OrderByBaseValue { get; set; }
```
### OrderByFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the order by field name.</p>


```csharp
public string OrderByFieldName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the time value.</p>


```csharp
public TimeValue TimeValue { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMosaicRule and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Viewpoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the viewpoint as a point.</p>


```csharp
public MapPoint Viewpoint { get; set; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Gets or sets the where clause as a string.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMosaicRule.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


