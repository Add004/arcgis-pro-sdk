# CIMGZDLabelGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Represents a UTM Grid Zone Designator Label definition for a MapGrid.</p>


## Object Signature

```csharp
public class CIMGZDLabelGridLine : CIMGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGZDLabelGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Represents a UTM Grid Zone Designator Label definition for a MapGrid.</p>


```csharp
public CIMGZDLabelGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGZDLabelGridLine.</p>


```csharp
public CIMGZDLabelGridLine Clone()
```
### DynamicStringTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the dynamic string used to represent the GZD label of the map grid.</p>


```csharp
public string DynamicStringTemplate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMGZDLabelGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMGZDLabelGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalCenterPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the horizontal position of the GZD label at the center of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition HorizontalCenterPosition { get; set; }
```
### HorizontalLeftPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the horizontal position of the GZD label at the left of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition HorizontalLeftPosition { get; set; }
```
### HorizontalRightPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the horizontal position of the GZD label at the right of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition HorizontalRightPosition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGZDLabelGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalBottomPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the vertical position of the GZD label at the bottom of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition VerticalBottomPosition { get; set; }
```
### VerticalCenterPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the vertical position of the GZD label at the center of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition VerticalCenterPosition { get; set; }
```
### VerticalTopPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Gets or sets the vertical position of the GZD label at the top of each UTM grid zone.</p>


```csharp
public CIMGridZoneLabelPosition VerticalTopPosition { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGZDLabelGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


