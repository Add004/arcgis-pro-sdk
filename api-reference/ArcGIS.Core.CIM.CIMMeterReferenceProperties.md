# CIMMeterReferenceProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Defines the display properties of the meter reference guide.</p>


## Object Signature

```csharp
public class CIMMeterReferenceProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMeterReferenceProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Defines the display properties of the meter reference guide.</p>


```csharp
public CIMMeterReferenceProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMeterReferenceProperties.</p>


```csharp
public CIMMeterReferenceProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMeterReferenceProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMeterReferenceProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridSquareHorizontalSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the horizontal separator value of the square identification area.</p>


```csharp
public int GridSquareHorizontalSeparator { get; set; }
```
### GridSquareHorizontalSeparatorDual

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the horizontal auxiliary separator value of the square identification area.</p>


```csharp
public int GridSquareHorizontalSeparatorDual { get; set; }
```
### GridSquareLowerLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the lower left corner of the square identification area.</p>


```csharp
public string GridSquareLowerLeft { get; set; }
```
### GridSquareLowerLeftDual

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the auxiliary text displayed in the lower left corner of the square identification area.</p>


```csharp
public string GridSquareLowerLeftDual { get; set; }
```
### GridSquareLowerRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the lower right corner of the square identification area.</p>


```csharp
public string GridSquareLowerRight { get; set; }
```
### GridSquareLowerRightDual

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the auxiliary text displayed in the lower right corner of the square identification area.</p>


```csharp
public string GridSquareLowerRightDual { get; set; }
```
### GridSquareUpperLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the upper left corner of the square identification area.</p>


```csharp
public string GridSquareUpperLeft { get; set; }
```
### GridSquareUpperLeftDual

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the auxiliary text displayed in the upper left corner of the square identification area.</p>


```csharp
public string GridSquareUpperLeftDual { get; set; }
```
### GridSquareUpperRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the upper right corner of the square identification area.</p>


```csharp
public string GridSquareUpperRight { get; set; }
```
### GridSquareUpperRightDual

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the auxiliary text displayed in the upper left corner of the square identification area.</p>


```csharp
public string GridSquareUpperRightDual { get; set; }
```
### GridSquareVerticalSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the vertical separator value of the square identification area.</p>


```csharp
public int GridSquareVerticalSeparator { get; set; }
```
### GridZoneLatitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the latitude of the grid zone.</p>


```csharp
public int GridZoneLatitude { get; set; }
```
### GridZoneLongitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the longitude of the grid zone.</p>


```csharp
public int GridZoneLongitude { get; set; }
```
### GridZoneLowerLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the lower left corner of the grid zone designation area.</p>


```csharp
public string GridZoneLowerLeft { get; set; }
```
### GridZoneLowerRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the lower right corner of the grid zone designation area.</p>


```csharp
public string GridZoneLowerRight { get; set; }
```
### GridZoneUpperLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the upper left corner of the grid zone designation area.</p>


```csharp
public string GridZoneUpperLeft { get; set; }
```
### GridZoneUpperRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Gets or sets the text displayed in the upper right corner of the grid zone designation area.</p>


```csharp
public string GridZoneUpperRight { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMeterReferenceProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeterReferenceProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


