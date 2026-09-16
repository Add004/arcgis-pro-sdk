# NAAttributeParameterValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Represents a network attribute parameter value. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAAttributeParameterValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAAttributeParameterValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Creates a new attribute parameter value object.</p>


```csharp
public NAAttributeParameterValue()
```
### NAAttributeParameterValue(string, string, int, object)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Creates a new attribute parameter value object from input parameters.</p>


```csharp
public NAAttributeParameterValue(string attributeName, string parameterName, int varType, object value = null)
```
### AttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the attribute name.</p>


```csharp
public string AttributeName { get; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Reconstructs the NAAttributeParameterValue with a specified state from a JSON encoding.</p>


```csharp
public static NAAttributeParameterValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### ParameterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the parameter names.</p>


```csharp
public string ParameterName { get; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAAttributeParameterValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the value.</p>


```csharp
public object Value { get; set; }
```
### VarType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the variant type.</p>


```csharp
public int VarType { get; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAAttributeParameterValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


