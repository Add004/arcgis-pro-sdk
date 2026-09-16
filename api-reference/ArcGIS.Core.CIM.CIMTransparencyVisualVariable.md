# CIMTransparencyVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Represents a transparency visual variable.</p>


## Object Signature

```csharp
public class CIMTransparencyVisualVariable : CIMVisualVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTransparencyVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Represents a transparency visual variable.</p>


```csharp
public CIMTransparencyVisualVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTransparencyVisualVariable.</p>


```csharp
public CIMTransparencyVisualVariable Clone()
```
### DataValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the data values.</p>


```csharp
public double[] DataValues { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the field to base the transparency on.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMTransparencyVisualVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMTransparencyVisualVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the normalization method.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTransparencyVisualVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TransparencyValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the transparency values that correspond to data values.</p>


```csharp
public double[] TransparencyValues { get; set; }
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTransparencyVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


