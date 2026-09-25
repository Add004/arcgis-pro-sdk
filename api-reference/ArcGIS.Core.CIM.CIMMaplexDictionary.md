# CIMMaplexDictionary

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Represents a Maplex dictionary.</p>


## Object Signature

```csharp
public class CIMMaplexDictionary : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexDictionary()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Represents a Maplex dictionary.</p>


```csharp
public CIMMaplexDictionary()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexDictionary.</p>


```csharp
public CIMMaplexDictionary Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexDictionary with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexDictionary FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaplexDictionary

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Gets or sets the Maplex dictionary entries.</p>


```csharp
public CIMMaplexDictionaryEntry[] MaplexDictionary { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Gets or sets the Maplex dictionary name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexDictionary and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionary.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


