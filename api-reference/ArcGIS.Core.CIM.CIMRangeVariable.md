# CIMRangeVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Represents a range variable.</p>


## Object Signature

```csharp
public class CIMRangeVariable : CIMBindVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRangeVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Represents a range variable.</p>


```csharp
public CIMRangeVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRangeVariable.</p>


```csharp
public CIMRangeVariable Clone()
```
### DefaultMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets the default maximum value.</p>


```csharp
public object DefaultMax { get; set; }
```
### DefaultMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets the default minimum value.</p>


```csharp
public object DefaultMin { get; set; }
```
### FieldExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets the field for which the value range will be specified.</p>


```csharp
public string FieldExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMRangeVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMRangeVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Optional

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this variable is optional. If not, default values must be provided.</p>


```csharp
public bool Optional { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets the name of the table to which the field in FieldExpression belongs.</p>


```csharp
public string TableName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRangeVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueIfMissing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the resulting expression should take if the variable is optional and no value is passed.</p>


```csharp
public bool ValueIfMissing { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRangeVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


