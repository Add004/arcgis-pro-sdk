# CIMCGAAttribute

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Represents a CGA attribute, the symbol attribute as specified by the CGA code in the rule package.</p>


## Object Signature

```csharp
public class CIMCGAAttribute : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCGAAttribute()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Represents a CGA attribute, the symbol attribute as specified by the CGA code in the rule package.</p>


```csharp
public CIMCGAAttribute()
```
### ArrayRowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Gets or sets the count of rows in the array. Used when CGAAttributeType is Float_Array, String_Array and Boolean_Array.</p>


```csharp
public int ArrayRowCount { get; set; }
```
### CGAAttributeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Gets or sets the CGA attribute type.</p>


```csharp
public CGAAttributeType CGAAttributeType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCGAAttribute.</p>


```csharp
public CIMCGAAttribute Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Reconstructs the CIMCGAAttribute with a specified state from a JSON encoding.</p>


```csharp
public static CIMCGAAttribute FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCGAAttribute and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Gets or sets the value. Used when CGAAttributeType is Float, String and Boolean.</p>


```csharp
public object Value { get; set; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Gets or sets the values in the array. Used when CGAAttributeType is Float_Array, String_Array and Boolean_Array.</p>


```csharp
public object[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCGAAttribute.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


