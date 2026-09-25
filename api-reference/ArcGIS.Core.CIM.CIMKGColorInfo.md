# CIMKGColorInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Color Info.</p>


## Object Signature

```csharp
public class CIMKGColorInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGColorInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Color Info.</p>


```csharp
public CIMKGColorInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGColorInfo.</p>


```csharp
public CIMKGColorInfo Clone()
```
### CustomItemColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Gets or sets the custom color of the parent type.</p>


```csharp
public CIMColor CustomItemColor { get; set; }
```
### CustomTextColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Gets or sets the custom text color of the parent type.</p>


```csharp
public CIMColor CustomTextColor { get; set; }
```
### DefaultItemColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Gets or sets the default item color of the parent type.</p>


```csharp
public CIMColor DefaultItemColor { get; set; }
```
### DefaultTextColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Gets or sets the default text color of the parent type.</p>


```csharp
public CIMColor DefaultTextColor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMKGColorInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGColorInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGColorInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseCustomColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the parent type is rendered using its custom colors.</p>


```csharp
public bool UseCustomColors { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGColorInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


