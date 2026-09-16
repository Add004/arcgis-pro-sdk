# CIMContiguousTabGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Defines a contiguous tab for a referenced grid.</p>


## Object Signature

```csharp
public class CIMContiguousTabGridLine : CIMTabGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMContiguousTabGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Defines a contiguous tab for a referenced grid.</p>


```csharp
public CIMContiguousTabGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMContiguousTabGridLine.</p>


```csharp
public CIMContiguousTabGridLine Clone()
```
### ContiguousTab

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Gets or sets the contiguous tab type.</p>


```csharp
public ContiguousTabType ContiguousTab { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMContiguousTabGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMContiguousTabGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMContiguousTabGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContiguousTabGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


