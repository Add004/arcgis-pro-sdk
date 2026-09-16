# CIMFormCodedValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Represents a set of valid coded values with unique names.</p>


## Object Signature

```csharp
public class CIMFormCodedValue : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormCodedValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Represents a set of valid coded values with unique names.</p>


```csharp
public CIMFormCodedValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormCodedValue.</p>


```csharp
public CIMFormCodedValue Clone()
```
### CodeAsDouble

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Gets or sets the value stored in the feature attribute.</p>


```csharp
public double CodeAsDouble { get; set; }
```
### CodeAsString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Gets or sets the value stored in the feature attribute.</p>


```csharp
public string CodeAsString { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Reconstructs the CIMFormCodedValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormCodedValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Gets or sets the user-friendly name for what the code means.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormCodedValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


