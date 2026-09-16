# CIMMapGeotriggerProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Represents geotrigger properties for a map.</p>


## Object Signature

```csharp
public class CIMMapGeotriggerProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapGeotriggerProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Represents geotrigger properties for a map.</p>


```csharp
public CIMMapGeotriggerProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapGeotriggerProperties.</p>


```csharp
public CIMMapGeotriggerProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMapGeotriggerProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapGeotriggerProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geotriggers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Gets or sets the geotriggers.</p>


```csharp
public CIMGeotrigger[] Geotriggers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapGeotriggerProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGeotriggerProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


