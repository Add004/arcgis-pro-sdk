# CIMIPSPathSnappingConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Defines IPS configuration path snapping properties.</p>


## Object Signature

```csharp
public class CIMIPSPathSnappingConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSPathSnappingConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Defines IPS configuration path snapping properties.</p>


```csharp
public CIMIPSPathSnappingConfiguration()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSPathSnappingConfiguration.</p>


```csharp
public CIMIPSPathSnappingConfiguration Clone()
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the distance for path snapping.</p>


```csharp
public double Distance { get; set; }
```
### DistanceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Gets or sets the distance unit for path snapping.</p>


```csharp
public LinearUnit DistanceUnit { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether path snapping property is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSPathSnappingConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSPathSnappingConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSPathSnappingConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPathSnappingConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


