# CIMBivariateRendererAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a bivariate choropleth renderer.</p>


## Object Signature

```csharp
public class CIMBivariateRendererAuthoringInfo : CIMUniqueValueRendererAuthoringInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBivariateRendererAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a bivariate choropleth renderer.</p>


```csharp
public CIMBivariateRendererAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBivariateRendererAuthoringInfo.</p>


```csharp
public CIMBivariateRendererAuthoringInfo Clone()
```
### FieldInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the field related properties used to generate the breaks.</p>


```csharp
public CIMBivariateFieldInfo[] FieldInfos { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMBivariateRendererAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMBivariateRendererAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLabelOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the grid label option.</p>


```csharp
public BivariateGridLegendLabelStrategy GridLabelOption { get; set; }
```
### GridOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the grid orientation.</p>


```csharp
public BivariateGridLegendOrientationType GridOrientation { get; set; }
```
### GridSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the grid size.</p>


```csharp
public BivariateGridSizeOption GridSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### TemplateSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the template symbol.</p>


```csharp
public CIMSymbolReference TemplateSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBivariateRendererAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBivariateRendererAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


