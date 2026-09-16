# CIMMaplexDictionaryEntry

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Represents a Maplex dictionary entry.</p>


## Object Signature

```csharp
public class CIMMaplexDictionaryEntry : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexDictionaryEntry()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Represents a Maplex dictionary entry.</p>


```csharp
public CIMMaplexDictionaryEntry()
```
### Abbreviation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Gets or sets the abbreviation.</p>


```csharp
public string Abbreviation { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexDictionaryEntry.</p>


```csharp
public CIMMaplexDictionaryEntry Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexDictionaryEntry with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexDictionaryEntry FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaplexAbbreviationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Gets or sets the abbreviation type.</p>


```csharp
public MaplexAbbreviationType MaplexAbbreviationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Gets or sets the text to abbreviate.</p>


```csharp
public string Text { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexDictionaryEntry and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexDictionaryEntry.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


