# CIMMapProductFeatureGuide

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Represents the Guide to Numbered (GNF) surround element.</p>


## Object Signature

```csharp
public class CIMMapProductFeatureGuide : CIMBaseStreetIndex, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapProductFeatureGuide()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Represents the Guide to Numbered (GNF) surround element.</p>


```csharp
public CIMMapProductFeatureGuide()
```
### AutoUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether properties of the surround should update automatically based on changes in the map.</p>


```csharp
public bool AutoUpdate { get; set; }
```
### CategoryCodeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets the Category Code field name.</p>


```csharp
public string CategoryCodeFieldName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapProductFeatureGuide.</p>


```csharp
public CIMMapProductFeatureGuide Clone()
```
### DrawToSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the element to specification size or allow user to manually resize element.</p>


```csharp
public bool DrawToSpecification { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Reconstructs the CIMMapProductFeatureGuide with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapProductFeatureGuide FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets the grid reference field name.</p>


```csharp
public CIMMapProductGridReference GridReference { get; set; }
```
### IDNumberFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets the Identification Number field name.</p>


```csharp
public string IDNumberFieldName { get; set; }
```
### ProductSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Gets or sets the map product specification type of the surround.</p>


```csharp
public MapProductSpecType ProductSpecification { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapProductFeatureGuide and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapProductFeatureGuide.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


