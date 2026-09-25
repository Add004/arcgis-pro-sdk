# CIMGridPattern

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Defines pattern for a component.</p>


## Object Signature

```csharp
public class CIMGridPattern : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridPattern()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Defines pattern for a component.</p>


```csharp
public CIMGridPattern()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridPattern.</p>


```csharp
public CIMGridPattern Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Reconstructs the CIMGridPattern with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridPattern FromJson(string json, JsonDeserializationSettings settings = null)
```
### Gap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Gets or sets the gap pattern of the component.</p>


```csharp
public double Gap { get; set; }
```
### Interval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Gets or sets the interval of the component the pattern represents.</p>


```csharp
public double Interval { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Start

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Gets or sets the start pattern of the component.</p>


```csharp
public double Start { get; set; }
```
### Stop

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Gets or sets the stop pattern of the component.</p>


```csharp
public double Stop { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridPattern and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridPattern.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


