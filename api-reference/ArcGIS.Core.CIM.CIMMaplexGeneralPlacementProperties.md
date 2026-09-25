# CIMMaplexGeneralPlacementProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Represents Maplex general placement properties.</p>


## Object Signature

```csharp
public class CIMMaplexGeneralPlacementProperties : CIMGeneralPlacementProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexGeneralPlacementProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Represents Maplex general placement properties.</p>


```csharp
public CIMMaplexGeneralPlacementProperties()
```
### AllowBorderOverlap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow border overlap.</p>


```csharp
public bool AllowBorderOverlap { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexGeneralPlacementProperties.</p>


```csharp
public CIMMaplexGeneralPlacementProperties Clone()
```
### Dictionaries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the Maplex dictionaries.</p>


```csharp
public CIMMaplexDictionary[] Dictionaries { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexGeneralPlacementProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexGeneralPlacementProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### KeyNumberGroups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the key number groups.</p>


```csharp
public CIMMaplexKeyNumberGroup[] KeyNumberGroups { get; set; }
```
### PlacementQuality

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the placement quality.</p>


```csharp
public MaplexQualityType PlacementQuality { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexGeneralPlacementProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexGeneralPlacementProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


