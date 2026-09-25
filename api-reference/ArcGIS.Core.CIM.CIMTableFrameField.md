# CIMTableFrameField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Display properties for fields in a table frame.</p>


## Object Signature

```csharp
public class CIMTableFrameField : CIMTableField, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableFrameField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Display properties for fields in a table frame.</p>


```csharp
public CIMTableFrameField()
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets the field background symbol.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### BorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets the field border symbol.</p>


```csharp
public CIMSymbolReference BorderSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTableFrameField.</p>


```csharp
public CIMTableFrameField Clone()
```
### EnableWordWrapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to wrap field values that don't fit the width.</p>


```csharp
public bool EnableWordWrapping { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Reconstructs the CIMTableFrameField with a specified state from a JSON encoding.</p>


```csharp
public static CIMTableFrameField FromJson(string json, JsonDeserializationSettings settings = null)
```
### HeadingTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets the field name/alias text symbol.</p>


```csharp
public CIMSymbolReference HeadingTextSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets the field value text symbol.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTableFrameField and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Gets or sets the symbol for vertical lines on sides of field.</p>


```csharp
public CIMSymbolReference VerticalLineSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableFrameField.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


