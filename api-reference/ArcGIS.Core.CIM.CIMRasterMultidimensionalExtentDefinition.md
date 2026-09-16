# CIMRasterMultidimensionalExtentDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Represents a multidimensional extent applicable to a raster layer.</p>


## Object Signature

```csharp
public class CIMRasterMultidimensionalExtentDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterMultidimensionalExtentDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Represents a multidimensional extent applicable to a raster layer.</p>


```csharp
public CIMRasterMultidimensionalExtentDefinition()
```
### AreaOfInterest

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Gets or sets the area of interest for the multidimensional extent.</p>


```csharp
public Geometry AreaOfInterest { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterMultidimensionalExtentDefinition.</p>


```csharp
public CIMRasterMultidimensionalExtentDefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterMultidimensionalExtentDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterMultidimensionalExtentDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubsetDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Gets or sets the dimensional definitions that define a multidimensional subset.</p>


```csharp
public CIMRasterDimensionalDefinition[] SubsetDefinitions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterMultidimensionalExtentDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalExtentDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


