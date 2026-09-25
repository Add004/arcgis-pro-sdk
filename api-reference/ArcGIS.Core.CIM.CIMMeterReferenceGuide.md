# CIMMeterReferenceGuide

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Provides a set of instructions and examples that enable users to compose standard grid reference.</p>


## Object Signature

```csharp
public class CIMMeterReferenceGuide : CIMMapProductSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMeterReferenceGuide()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Provides a set of instructions and examples that enable users to compose standard grid reference.</p>


```csharp
public CIMMeterReferenceGuide()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMeterReferenceGuide.</p>


```csharp
public CIMMeterReferenceGuide Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Reconstructs the CIMMeterReferenceGuide with a specified state from a JSON encoding.</p>


```csharp
public static CIMMeterReferenceGuide FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridSquareType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets the type of the 100,000-Square identification area.</p>


```csharp
public MeterReferenceSquareType GridSquareType { get; set; }
```
### IsSingleGridZone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the grid zone is using single (true) or multiple (false) designators.</p>


```csharp
public bool IsSingleGridZone { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for the grid lines in the meter reference guide.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### MapIndexLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets the layer used to define the area of interest for calculating intersecting MGRS values.</p>


```csharp
public string MapIndexLayerURI { get; set; }
```
### Properties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets the display properties of the meter reference guide.</p>


```csharp
public CIMMeterReferenceProperties Properties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for the text elements in the meter reference guide.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMeterReferenceGuide and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceGuide.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


