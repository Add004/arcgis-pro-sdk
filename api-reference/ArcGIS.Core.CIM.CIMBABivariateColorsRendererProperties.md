# CIMBABivariateColorsRendererProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer bivariate colors renderer properties.</p>


## Object Signature

```csharp
public class CIMBABivariateColorsRendererProperties : CIMBARendererProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBABivariateColorsRendererProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer bivariate colors renderer properties.</p>


```csharp
public CIMBABivariateColorsRendererProperties()
```
### ClassificationFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification field names in the levels of detail feature classes.</p>


```csharp
public string[] ClassificationFields { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBABivariateColorsRendererProperties.</p>


```csharp
public CIMBABivariateColorsRendererProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMBABivariateColorsRendererProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMBABivariateColorsRendererProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the grid size.</p>


```csharp
public BivariateGridSizeOption GridSize { get; set; }
```
### OrientationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the orientation type.</p>


```csharp
public BivariateGridLegendOrientationType OrientationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBABivariateColorsRendererProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBABivariateColorsRendererProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


