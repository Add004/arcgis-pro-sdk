# CIMBivariateFieldInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Contains a collection of properties that describe a bivariate attribute field.</p>


## Object Signature

```csharp
public class CIMBivariateFieldInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBivariateFieldInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Contains a collection of properties that describe a bivariate attribute field.</p>


```csharp
public CIMBivariateFieldInfo()
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBivariateFieldInfo.</p>


```csharp
public CIMBivariateFieldInfo Clone()
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the default label used for the legend.</p>


```csharp
public string DefaultLabel { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the field for rendering.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMBivariateFieldInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMBivariateFieldInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the minimum break.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the normalization type.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### NumberOfHistogramBins

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the number of bins displayed in the histogram.</p>


```csharp
public int NumberOfHistogramBins { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBivariateFieldInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpperBounds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets the collection of upper bounds.</p>


```csharp
public double[] UpperBounds { get; set; }
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number. When both Field and ValueExpressionInfo are present ValueExpressionInfo is used.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateFieldInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


