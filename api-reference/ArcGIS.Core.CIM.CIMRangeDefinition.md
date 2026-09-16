# CIMRangeDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Represents a range definition.</p>


## Object Signature

```csharp
public class CIMRangeDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRangeDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Represents a range definition.</p>


```csharp
public CIMRangeDefinition()
```
### AliasExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns a string representing range alias value.</p>


```csharp
public CIMExpressionInfo AliasExpressionInfo { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRangeDefinition.</p>


```csharp
public CIMRangeDefinition Clone()
```
### CurrentRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the current range.</p>


```csharp
public CIMRange CurrentRange { get; set; }
```
### CurrentRangeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the current range relation.</p>


```csharp
public RangeRelation CurrentRangeRelation { get; set; }
```
### CustomFullExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the custom full extent.</p>


```csharp
public CIMRange CustomFullExtent { get; set; }
```
### EndFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the end field name.</p>


```csharp
public string EndFieldName { get; set; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the field name. Used as the start field name when an end field name is set.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMRangeDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMRangeDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsExclusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not range is exclusion.</p>


```csharp
public bool IsExclusion { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRangeDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UniqueValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Gets or sets a cached set of unique range values.</p>


```csharp
public double[] UniqueValues { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


