# CIMSizeVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Represents a size visual variable.</p>


## Object Signature

```csharp
public class CIMSizeVisualVariable : CIMVisualVariable, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p>
    VariableType = Graduated use expression, Minimum/Maximum size, Minimum/Maximum value.
    </p>
<p>
    VariableType = Proportional, unit defined use Expression, ValueUnit, ValueShape, ValueRepresentation.
    </p>
<p>
    VariableType = Proportional, unit NOT defined use Expression, MinSize, MinValue, could use MaxSize.
    </p>


## Members

### CIMSizeVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Represents a size visual variable.</p>


```csharp
public CIMSizeVisualVariable()
```
### Axis

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets size visual variable axis.</p>


```csharp
public SizeVisualVariableAxis Axis { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSizeVisualVariable.</p>


```csharp
public CIMSizeVisualVariable Clone()
```
### DataValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the data values.</p>


```csharp
public double[] DataValues { get; set; }
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the expression.</p>


```csharp
public string Expression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMSizeVisualVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMSizeVisualVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the maximum size.</p>


```csharp
public double MaxSize { get; set; }
```
### MaxValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double MaxValue { get; set; }
```
### MinSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the minimum size.</p>


```csharp
public double MinSize { get; set; }
```
### MinValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the minimum value.</p>


```csharp
public double MinValue { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the data normalization method.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### RandomMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the random maximum.</p>


```csharp
public double RandomMax { get; set; }
```
### RandomMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the random minimum.</p>


```csharp
public double RandomMin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SizeValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the size values that correspond to data values.</p>


```csharp
public double[] SizeValues { get; set; }
```
### Target

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets size visual variable target which specifies the portion of the symbol targeted for sizing.</p>


```csharp
public string Target { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSizeVisualVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### ValueRepresentation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the value representations.</p>


```csharp
public ValueRepresentations ValueRepresentation { get; set; }
```
### ValueShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the value shape.</p>


```csharp
public SymbolShapes ValueShape { get; set; }
```
### ValueUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the size visual variable type.</p>


```csharp
public LinearUnit ValueUnits { get; set; }
```
### VariableType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Gets or sets size visual variable type.</p>


```csharp
public SizeVisualVariableType VariableType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSizeVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


