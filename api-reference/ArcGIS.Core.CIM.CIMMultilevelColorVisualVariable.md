# CIMMultilevelColorVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Represents a color visual variable with different levels-of-detail.</p>


## Object Signature

```csharp
public class CIMMultilevelColorVisualVariable : CIMMultilevelVisualVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultilevelColorVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Represents a color visual variable with different levels-of-detail.</p>


```csharp
public CIMMultilevelColorVisualVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultilevelColorVisualVariable.</p>


```csharp
public CIMMultilevelColorVisualVariable Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMMultilevelColorVisualVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultilevelColorVisualVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the data normalization method.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### PolygonSymbolColorTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the property that controls how the color ramp is applied to polygon symbols.</p>


```csharp
public PolygonSymbolColorTarget PolygonSymbolColorTarget { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultilevelColorVisualVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelColorVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


