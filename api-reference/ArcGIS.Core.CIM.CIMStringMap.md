# CIMStringMap

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Represents a string map of key value pairs.</p>


## Object Signature

```csharp
public class CIMStringMap : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStringMap()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Represents a string map of key value pairs.</p>


```csharp
public CIMStringMap()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStringMap.</p>


```csharp
public CIMStringMap Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Reconstructs the CIMStringMap with a specified state from a JSON encoding.</p>


```csharp
public static CIMStringMap FromJson(string json, JsonDeserializationSettings settings = null)
```
### Key

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Gets or sets the key.</p>


```csharp
public string Key { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStringMap and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Gets or sets the value.</p>


```csharp
public string Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStringMap.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


