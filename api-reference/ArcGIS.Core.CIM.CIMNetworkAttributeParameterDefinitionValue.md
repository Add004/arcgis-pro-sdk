# CIMNetworkAttributeParameterDefinitionValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Provides access to read or update the value assigned to a network parameter of a network attribute.</p>


## Object Signature

```csharp
public class CIMNetworkAttributeParameterDefinitionValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkAttributeParameterDefinitionValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Provides access to read or update the value assigned to a network parameter of a network attribute.</p>


```csharp
public CIMNetworkAttributeParameterDefinitionValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkAttributeParameterDefinitionValue.</p>


```csharp
public CIMNetworkAttributeParameterDefinitionValue Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkAttributeParameterDefinitionValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkAttributeParameterDefinitionValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsRestrictionUsage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is a restriction usage type network parameter.</p>


```csharp
public bool IsRestrictionUsage { get; set; }
```
### NetworkAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Gets or sets the network attribute name.</p>


```csharp
public string NetworkAttributeName { get; set; }
```
### NetworkParameterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Gets or sets the network parameter name.</p>


```csharp
public string NetworkParameterName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkAttributeParameterDefinitionValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Gets or sets the value. The type of the value should correspond with the ValueType property or be null.</p>


```csharp
public object Value { get; set; }
```
### ValueType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Gets or sets the value type. Supports: Short, Long, Float, Double, Date, String, Bool.</p>


```csharp
public ValueType ValueType { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkAttributeParameterDefinitionValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


