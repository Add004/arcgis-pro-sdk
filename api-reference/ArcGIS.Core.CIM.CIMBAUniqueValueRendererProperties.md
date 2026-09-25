# CIMBAUniqueValueRendererProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer unique values renderer properties.</p>


## Object Signature

```csharp
public class CIMBAUniqueValueRendererProperties : CIMBARendererProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAUniqueValueRendererProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer unique values renderer properties.</p>


```csharp
public CIMBAUniqueValueRendererProperties()
```
### ClassificationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification field name in the levels of detail feature classes.</p>


```csharp
public string ClassificationField { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAUniqueValueRendererProperties.</p>


```csharp
public CIMBAUniqueValueRendererProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMBAUniqueValueRendererProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAUniqueValueRendererProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAUniqueValueRendererProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAUniqueValueRendererProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


