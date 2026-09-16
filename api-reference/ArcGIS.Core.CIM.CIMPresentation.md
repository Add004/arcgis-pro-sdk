# CIMPresentation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Represents a presentation.</p>


## Object Signature

```csharp
public class CIMPresentation : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Represents a presentation.</p>


```csharp
public CIMPresentation()
```
### AspectRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the aspect ratio.</p>


```csharp
public CIMAspectRatio AspectRatio { get; set; }
```
### CMYKColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the name of the CMYK color profile for a presentation.</p>


```csharp
public string CMYKColorProfile { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentation.</p>


```csharp
public CIMPresentation Clone()
```
### ColorModel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the color model for a presentation.</p>


```csharp
public ColorModel ColorModel { get; set; }
```
### ColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode.</p>


```csharp
public ColorVisionDeficiencyType ColorVisionDeficiencyMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentation with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentation FromJson(string json, JsonDeserializationSettings settings = null)
```
### PageSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the page settings for the presentation.</p>


```csharp
public CIMPage PageSettings { get; set; }
```
### Pages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the presentation pages as an array of repository URIs.</p>


```csharp
public string[] Pages { get; set; }
```
### RGBColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Gets or sets the name of the RGB color profile for a presentation.</p>


```csharp
public string RGBColorProfile { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


