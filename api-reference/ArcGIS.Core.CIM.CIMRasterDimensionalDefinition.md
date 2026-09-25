# CIMRasterDimensionalDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Represents a set of criteria used to define the multidimensional extent of a raster layer.</p>


## Object Signature

```csharp
public class CIMRasterDimensionalDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterDimensionalDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Represents a set of criteria used to define the multidimensional extent of a raster layer.</p>


```csharp
public CIMRasterDimensionalDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterDimensionalDefinition.</p>


```csharp
public CIMRasterDimensionalDefinition Clone()
```
### DimensionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the dimension.</p>


```csharp
public string DimensionName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterDimensionalDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterDimensionalDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum dimension values.</p>


```csharp
public double[] MaximumValues { get; set; }
```
### MinimumValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Gets or sets the minimum dimension values.</p>


```csharp
public double[] MinimumValues { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterDimensionalDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the variable.</p>


```csharp
public string VariableName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterDimensionalDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


