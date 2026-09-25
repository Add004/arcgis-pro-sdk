# CIMRasterColorizerMapping

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Represents a raster colorizer mapping.</p>


## Object Signature

```csharp
public class CIMRasterColorizerMapping : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterColorizerMapping()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Represents a raster colorizer mapping.</p>


```csharp
public CIMRasterColorizerMapping()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterColorizerMapping.</p>


```csharp
public CIMRasterColorizerMapping Clone()
```
### ColorizerIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Gets or sets the index of the colorizer.</p>


```csharp
public int ColorizerIndex { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterColorizerMapping with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterColorizerMapping FromJson(string json, JsonDeserializationSettings settings = null)
```
### RasterOID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Gets or sets the Object ID of the raster in the raster catalog.</p>


```csharp
public int RasterOID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterColorizerMapping and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorizerMapping.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


