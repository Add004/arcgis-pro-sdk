# CIMKGEventErrorHandling

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Defines the behaviours when event time(s) are missing or wrong.</p>


## Object Signature

```csharp
public class CIMKGEventErrorHandling : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGEventErrorHandling()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Defines the behaviours when event time(s) are missing or wrong.</p>


```csharp
public CIMKGEventErrorHandling()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGEventErrorHandling.</p>


```csharp
public CIMKGEventErrorHandling Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Reconstructs the CIMKGEventErrorHandling with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGEventErrorHandling FromJson(string json, JsonDeserializationSettings settings = null)
```
### KGDurativeEventMissingOneTimeBehaviour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Gets or sets the behaviour when a durative event has one missing time.</p>


```csharp
public KGDurativeEventMissingOneTimeBehaviour KGDurativeEventMissingOneTimeBehaviour { get; set; }
```
### KGDurativeEventSwappedTimesBehaviour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Gets or sets the behaviour when a durative event has swapped times.</p>


```csharp
public KGDurativeEventSwappedTimesBehaviour KGDurativeEventSwappedTimesBehaviour { get; set; }
```
### KGEventMissingAllTimesBehaviour

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Gets or sets the behaviour when an event has no time.</p>


```csharp
public KGEventMissingAllTimesBehaviour KGEventMissingAllTimesBehaviour { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGEventErrorHandling and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventErrorHandling.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


