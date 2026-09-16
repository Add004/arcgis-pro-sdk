# CIMMaplexKeyNumberGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Represents a Maplex key number group.</p>


## Object Signature

```csharp
public class CIMMaplexKeyNumberGroup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexKeyNumberGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Represents a Maplex key number group.</p>


```csharp
public CIMMaplexKeyNumberGroup()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexKeyNumberGroup.</p>


```csharp
public CIMMaplexKeyNumberGroup Clone()
```
### DelimiterCharacter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the delimiter character of the key number.</p>


```csharp
public string DelimiterCharacter { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexKeyNumberGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexKeyNumberGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the horizontal alignment.</p>


```csharp
public MaplexKeyNumberHorizontalAlignment HorizontalAlignment { get; set; }
```
### KeyNumberMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the key numbering method.</p>


```csharp
public MaplexKeyNumberMethod KeyNumberMethod { get; set; }
```
### MaximumNumberOfLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the maximum number of lines.</p>


```csharp
public int MaximumNumberOfLines { get; set; }
```
### MinimumNumberOfLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the minimum number of lines.</p>


```csharp
public int MinimumNumberOfLines { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the name of the group.</p>


```csharp
public string Name { get; set; }
```
### NumberResetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Gets or sets the number reset type.</p>


```csharp
public MaplexKeyNumberResetType NumberResetType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexKeyNumberGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexKeyNumberGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


