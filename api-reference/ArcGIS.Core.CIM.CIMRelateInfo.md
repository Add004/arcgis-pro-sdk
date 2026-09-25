# CIMRelateInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Represents relate info.</p>


## Object Signature

```csharp
public class CIMRelateInfo : CIMRelateInfoBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRelateInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Represents relate info.</p>


```csharp
public CIMRelateInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRelateInfo.</p>


```csharp
public CIMRelateInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMRelateInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMRelateInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRelateInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRelateInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


