# CIMRange

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Represents a range.</p>


## Object Signature

```csharp
public class CIMRange : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRange()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Represents a range.</p>


```csharp
public CIMRange()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRange.</p>


```csharp
public CIMRange Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Reconstructs the CIMRange with a specified state from a JSON encoding.</p>


```csharp
public static CIMRange FromJson(string json, JsonDeserializationSettings settings = null)
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Gets or sets the maximum.</p>


```csharp
public double Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Gets or sets the minimum.</p>


```csharp
public double Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRange and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRange.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


