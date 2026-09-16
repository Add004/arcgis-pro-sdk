# CIMParagraphTextGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Represents a paragraph text graphic.</p>


## Object Signature

```csharp
public class CIMParagraphTextGraphic : CIMTextGraphicBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMParagraphTextGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Represents a paragraph text graphic.</p>


```csharp
public CIMParagraphTextGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMParagraphTextGraphic.</p>


```csharp
public CIMParagraphTextGraphic Clone()
```
### ColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Gets or sets number of columns in the paragraph text graphic.</p>


```csharp
public int ColumnCount { get; set; }
```
### ColumnGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Gets or sets the gap between columns.</p>


```csharp
public double ColumnGap { get; set; }
```
### Frame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic frame of the paragraph text graphic.</p>


```csharp
public CIMGraphicFrame Frame { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMParagraphTextGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMParagraphTextGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Gets or sets the margin of the paragraph text graphic.</p>


```csharp
public double Margin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMParagraphTextGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParagraphTextGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


