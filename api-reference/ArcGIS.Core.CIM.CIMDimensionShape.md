# CIMDimensionShape

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Represents a dimension shape as used by a dimension feature.</p>


## Object Signature

```csharp
public class CIMDimensionShape : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDimensionShape()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Represents a dimension shape as used by a dimension feature.</p>


```csharp
public CIMDimensionShape()
```
### BeginDimensionPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the begin dimension point.</p>


```csharp
public MapPoint BeginDimensionPoint { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDimensionShape.</p>


```csharp
public CIMDimensionShape Clone()
```
### DimensionLinePoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the point which describes the height of the dimension line.</p>


```csharp
public MapPoint DimensionLinePoint { get; set; }
```
### EndDimensionPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the end dimension point.</p>


```csharp
public MapPoint EndDimensionPoint { get; set; }
```
### ExtensionLineAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the angle of the extension lines in radians.</p>


```csharp
public double ExtensionLineAngle { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Reconstructs the CIMDimensionShape with a specified state from a JSON encoding.</p>


```csharp
public static CIMDimensionShape FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the angle of the text in radians.</p>


```csharp
public double TextAngle { get; set; }
```
### TextPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Gets or sets the point for the text placement.</p>


```csharp
public MapPoint TextPoint { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDimensionShape and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDimensionShape.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


