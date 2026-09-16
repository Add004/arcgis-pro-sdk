# CIMBinaryReference

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Represents a binary reference in a document.</p>


## Object Signature

```csharp
public class CIMBinaryReference : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBinaryReference()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Represents a binary reference in a document.</p>


```csharp
public CIMBinaryReference()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBinaryReference.</p>


```csharp
public CIMBinaryReference Clone()
```
### Data

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Gets or sets the base64 encoded data of the binary reference.</p>


```csharp
public string Data { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Reconstructs the CIMBinaryReference with a specified state from a JSON encoding.</p>


```csharp
public static CIMBinaryReference FromJson(string json, JsonDeserializationSettings settings = null)
```
### Object

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Gets or sets the stored CIM object.</p>


```csharp
public CIMObject Object { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBinaryReference and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference. Typically set by the system but used as a reference path.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinaryReference.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


