# CIMFormCodedValueDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Represents a coded value domain, which includes both the actual value that is stored in the database
and the description of what the coded value means.</p>


## Object Signature

```csharp
public class CIMFormCodedValueDomain : CIMFormDomain, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormCodedValueDomain()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Represents a coded value domain, which includes both the actual value that is stored in the database
and the description of what the coded value means.</p>


```csharp
public CIMFormCodedValueDomain()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormCodedValueDomain.</p>


```csharp
public CIMFormCodedValueDomain Clone()
```
### CodedValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Gets or sets a set of valid values with unique names.</p>


```csharp
public CIMFormCodedValue[] CodedValues { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Reconstructs the CIMFormCodedValueDomain with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormCodedValueDomain FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Gets or sets the domain name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormCodedValueDomain and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormCodedValueDomain.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


