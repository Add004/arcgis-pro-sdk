# CIMElementStorage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Represents a series of graphic elements stored offline.</p>


## Object Signature

```csharp
public class CIMElementStorage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMElementStorage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Represents a series of graphic elements stored offline.</p>


```csharp
public CIMElementStorage()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMElementStorage.</p>


```csharp
public CIMElementStorage Clone()
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Gets or sets a collection of elements.</p>


```csharp
public CIMElement[] Elements { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Reconstructs the CIMElementStorage with a specified state from a JSON encoding.</p>


```csharp
public static CIMElementStorage FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Gets or sets the graphics' spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### Symbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Gets or sets the symbols used by graphic elements.</p>


```csharp
public CIMSymbolIdentifier[] Symbols { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMElementStorage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElementStorage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


