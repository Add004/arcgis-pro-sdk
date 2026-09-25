# CIMS101DisplaySettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Represents S-101 portrayal settings.</p>


## Object Signature

```csharp
public class CIMS101DisplaySettings : CIMENCDisplaySettings, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMS101DisplaySettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Represents S-101 portrayal settings.</p>


```csharp
public CIMS101DisplaySettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMS101DisplaySettings.</p>


```csharp
public CIMS101DisplaySettings Clone()
```
### ColorPalette

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the color palette value.</p>


```csharp
public string ColorPalette { get; set; }
```
### ContextParameters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the catalogue context parameter values.</p>


```csharp
public IDictionary<string, object> ContextParameters { get; set; }
```
### DisplayMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the display mode value.</p>


```csharp
public string DisplayMode { get; set; }
```
### DisplayPlanes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the catalogue display plane values.</p>


```csharp
public IDictionary<string, object> DisplayPlanes { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Reconstructs the CIMS101DisplaySettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMS101DisplaySettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMS101DisplaySettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewingGroupLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the catalogue viewing group layer values.</p>


```csharp
public IDictionary<string, object> ViewingGroupLayers { get; set; }
```
### ViewingGroups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Gets or sets the catalogue viewing group values.</p>


```csharp
public IDictionary<string, object> ViewingGroups { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMS101DisplaySettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


