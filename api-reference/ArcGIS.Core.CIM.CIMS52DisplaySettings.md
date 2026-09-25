# CIMS52DisplaySettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Represents S-52 display settings.</p>


## Object Signature

```csharp
public class CIMS52DisplaySettings : CIMENCDisplaySettings, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMS52DisplaySettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Represents S-52 display settings.</p>


```csharp
public CIMS52DisplaySettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMS52DisplaySettings.</p>


```csharp
public CIMS52DisplaySettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Reconstructs the CIMS52DisplaySettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMS52DisplaySettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarinerSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the S-52 display properties for the layer.</p>


```csharp
public CIMS52MarinerSettings MarinerSettings { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextGroupVisibilitySettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the S-52 text group properties for the layer.</p>


```csharp
public CIMS52TextGroupVisibilitySettings TextGroupVisibilitySettings { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMS52DisplaySettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewingGroupSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the S-52 view group properties for the layer.</p>


```csharp
public CIMS52ViewingGroupSettings ViewingGroupSettings { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS52DisplaySettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


