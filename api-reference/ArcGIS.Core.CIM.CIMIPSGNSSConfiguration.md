# CIMIPSGNSSConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Define IPS configuration GNSS properties.</p>


## Object Signature

```csharp
public class CIMIPSGNSSConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSGNSSConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Define IPS configuration GNSS properties.</p>


```csharp
public CIMIPSGNSSConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSGNSSConfiguration.</p>


```csharp
public CIMIPSGNSSConfiguration Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether GNSS property is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSGNSSConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSGNSSConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSGNSSConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSGNSSConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


