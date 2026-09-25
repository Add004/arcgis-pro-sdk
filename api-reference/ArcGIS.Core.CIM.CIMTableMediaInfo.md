# CIMTableMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Represents table media info.</p>


## Object Signature

```csharp
public class CIMTableMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Represents table media info.</p>


```csharp
public CIMTableMediaInfo()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTableMediaInfo.</p>


```csharp
public CIMTableMediaInfo Clone()
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the fields.</p>


```csharp
public string[] Fields { get; set; }
```
### FieldsFontInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the font information for the Fields.</p>


```csharp
public string FieldsFontInfo { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMTableMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMTableMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTableMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseLayerFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the table is generated using the layer's visible fields.</p>


```csharp
public bool UseLayerFields { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


