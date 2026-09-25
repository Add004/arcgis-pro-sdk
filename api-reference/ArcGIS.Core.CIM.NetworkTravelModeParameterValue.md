# NetworkTravelModeParameterValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Represents a network travel mode parameter value. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
[DataContract]
public sealed class NetworkTravelModeParameterValue
```


## Members

### NetworkTravelModeParameterValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Creates a new network travel mode parameter value.</p>


```csharp
public NetworkTravelModeParameterValue()
```
### NetworkTravelModeParameterValue(string, string, object)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Creates a new network travel mode parameter value from input parameters.</p>


```csharp
public NetworkTravelModeParameterValue(string attributeName, string parameterName, object value = null)
```
### AttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the attribute name.</p>


```csharp
[DataMember(Name = "attributeName", Order = 0, IsRequired = false, EmitDefaultValue = true)]
public string AttributeName { get; set; }
```
### ConvertToPropertyValue(object, VarEnum)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Converts the source value of the specified type from the serialize value to the property value representation.</p>


```csharp
public static object ConvertToPropertyValue(object sourceValue, VarEnum varTypeEnumValue)
```
### ConvertToSerializeValue(object, VarEnum)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Converts the source value of the specified type from the property value to the serialize value representation.</p>


```csharp
public static object ConvertToSerializeValue(object sourceValue, VarEnum varTypeEnumValue)
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Reconstructs the NetworkTravelModeParameterValue with a specified state from a JSON encoding.</p>


```csharp
public static NetworkTravelModeParameterValue FromJson(string json)
```
### ParameterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the parameter name.</p>


```csharp
[DataMember(Name = "parameterName", Order = 1, IsRequired = false, EmitDefaultValue = true)]
public string ParameterName { get; set; }
```
### SerializeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the serialize value.</p>


```csharp
[DataMember(Name = "value", Order = 2, IsRequired = false, EmitDefaultValue = true)]
public object SerializeValue { get; set; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NetworkTravelModeParameterValue and its current state.</p>


```csharp
public string ToJson()
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">JSON encoding of the NetworkTravelModeParameterValue and its current state.</p>


```csharp
public override string ToString()
```
### TryConvertToPropertyValue(object, VarEnum, out object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Attempts to convert the source value of the specified type from the serialize value to the property value representation. Returns true if the conversion succeeded. Otherwise returns false.</p>


```csharp
public static bool TryConvertToPropertyValue(object sourceValue, VarEnum varTypeEnumValue, out object propertyValue)
```
### TryConvertToSerializeValue(object, VarEnum, out object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Attempts to convert the source value of the specified type from the property value to the serialize value representation. Returns true if the conversion succeeded. Otherwise returns false.</p>


```csharp
public static bool TryConvertToSerializeValue(object sourceValue, VarEnum varTypeEnumValue, out object serializeValue)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelModeParameterValue.yml" sourcestartlinenumber="1">Gets and sets the value.</p>


```csharp
public object Value { get; set; }
```


