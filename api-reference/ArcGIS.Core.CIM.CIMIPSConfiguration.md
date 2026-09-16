# CIMIPSConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Defines the properties for the IPS configuration.</p>


## Object Signature

```csharp
public class CIMIPSConfiguration : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSConfiguration()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Defines the properties for the IPS configuration.</p>


```csharp
public CIMIPSConfiguration()
```
### AppleIPS

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Gets or sets IPS configuration AppleIPS.</p>


```csharp
public CIMIPSAppleIPSConfiguration AppleIPS { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSConfiguration.</p>


```csharp
public CIMIPSConfiguration Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSConfiguration with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSConfiguration FromJson(string json, JsonDeserializationSettings settings = null)
```
### GNSS

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Gets or sets IPS configuration GNSS.</p>


```csharp
public CIMIPSGNSSConfiguration GNSS { get; set; }
```
### PathSnapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Gets or sets IPS configuration path snapping.</p>


```csharp
public CIMIPSPathSnappingConfiguration PathSnapping { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Smoothing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Gets or sets IPS configuration smoothing.</p>


```csharp
public CIMIPSSmoothingConfiguration Smoothing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSConfiguration and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSConfiguration.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


