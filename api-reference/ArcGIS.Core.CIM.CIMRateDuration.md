# CIMRateDuration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Provides access to properties of a rate duration.</p>


## Object Signature

```csharp
public class CIMRateDuration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRateDuration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Provides access to properties of a rate duration.</p>


```csharp
public CIMRateDuration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRateDuration.</p>


```csharp
public CIMRateDuration Clone()
```
### Duration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Gets or sets the duration.</p>


```csharp
public double Duration { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Reconstructs the CIMRateDuration with a specified state from a JSON encoding.</p>


```csharp
public static CIMRateDuration FromJson(string json, JsonDeserializationSettings settings = null)
```
### Rate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Gets or sets the rate.</p>


```csharp
public double Rate { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRateDuration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateDuration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


