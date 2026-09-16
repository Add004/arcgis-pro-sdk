# CIMTimeDisplayDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Represents a time display definition.</p>


## Object Signature

```csharp
public class CIMTimeDisplayDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimeDisplayDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Represents a time display definition.</p>


```csharp
public CIMTimeDisplayDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimeDisplayDefinition.</p>


```csharp
public CIMTimeDisplayDefinition Clone()
```
### Cumulative

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether time is cumulative.</p>


```csharp
public bool Cumulative { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMTimeDisplayDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimeDisplayDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the time interval.</p>


```csharp
public double TimeInterval { get; set; }
```
### TimeIntervalUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the time interval units.</p>


```csharp
public esriTimeUnits TimeIntervalUnits { get; set; }
```
### TimeOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the time offset.</p>


```csharp
public double TimeOffset { get; set; }
```
### TimeOffsetUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets the time offset units.</p>


```csharp
public esriTimeUnits TimeOffsetUnits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimeDisplayDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UniqueTimes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Gets or sets a cached set of unique OLE date values.</p>


```csharp
public double[] UniqueTimes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDisplayDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


