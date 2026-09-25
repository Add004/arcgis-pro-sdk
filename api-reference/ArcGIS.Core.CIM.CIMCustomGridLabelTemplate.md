# CIMCustomGridLabelTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Defines the label template for custom grids.</p>


## Object Signature

```csharp
public class CIMCustomGridLabelTemplate : CIMGridLabelTemplate, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCustomGridLabelTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Defines the label template for custom grids.</p>


```csharp
public CIMCustomGridLabelTemplate()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCustomGridLabelTemplate.</p>


```csharp
public CIMCustomGridLabelTemplate Clone()
```
### EdgeLabelAngles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the list of label angles to set the text symbol angle for each grid edge.</p>


```csharp
public double[] EdgeLabelAngles { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Reconstructs the CIMCustomGridLabelTemplate with a specified state from a JSON encoding.</p>


```csharp
public static CIMCustomGridLabelTemplate FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the label expression. Either a simple field name or an Arcade expression.</p>


```csharp
public CIMExpressionInfo LabelExpressionInfo { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the symbol of the label.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCustomGridLabelTemplate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomGridLabelTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


