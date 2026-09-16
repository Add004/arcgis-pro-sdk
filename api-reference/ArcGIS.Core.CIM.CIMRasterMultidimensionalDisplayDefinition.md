# CIMRasterMultidimensionalDisplayDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Represents a multidimensional display definition for the current display slice.</p>


## Object Signature

```csharp
public class CIMRasterMultidimensionalDisplayDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterMultidimensionalDisplayDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Represents a multidimensional display definition for the current display slice.</p>


```csharp
public CIMRasterMultidimensionalDisplayDefinition()
```
### AdditionalDimensionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the additional range dimension values for the current display slice.</p>


```csharp
public CIMRangeDimensionValue[] AdditionalDimensionValues { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterMultidimensionalDisplayDefinition.</p>


```csharp
public CIMRasterMultidimensionalDisplayDefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterMultidimensionalDisplayDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterMultidimensionalDisplayDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### HasRangeDimension

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the active variable has a range dimension.</p>


```csharp
public bool HasRangeDimension { get; set; }
```
### RangeDimensionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the selected range dimension.</p>


```csharp
public string RangeDimensionName { get; set; }
```
### RangeDimensionValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the selected range dimension value for the current display slice.</p>


```csharp
public CIMRange RangeDimensionValue { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the time value for the current display slice.</p>


```csharp
public TimeExtent TimeValue { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterMultidimensionalDisplayDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the variable.</p>


```csharp
public string VariableName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterMultidimensionalDisplayDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


