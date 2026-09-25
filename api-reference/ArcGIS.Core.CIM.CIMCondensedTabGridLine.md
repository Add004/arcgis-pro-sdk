# CIMCondensedTabGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Defines a condensed tab.</p>


## Object Signature

```csharp
public class CIMCondensedTabGridLine : CIMTabGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCondensedTabGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Defines a condensed tab.</p>


```csharp
public CIMCondensedTabGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCondensedTabGridLine.</p>


```csharp
public CIMCondensedTabGridLine Clone()
```
### CondensedTab

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Gets or sets the type of condensed tab.</p>


```csharp
public CondensedTabType CondensedTab { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMCondensedTabGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMCondensedTabGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCondensedTabGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Gets or sets the width of the tab. The width is in page units.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCondensedTabGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


