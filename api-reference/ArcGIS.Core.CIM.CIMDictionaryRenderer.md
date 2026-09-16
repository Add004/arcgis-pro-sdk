# CIMDictionaryRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Represents a dictionary renderer where symbols are drawn from a symbol dictionary.</p>


## Object Signature

```csharp
public class CIMDictionaryRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDictionaryRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Represents a dictionary renderer where symbols are drawn from a symbol dictionary.</p>


```csharp
public CIMDictionaryRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDictionaryRenderer.</p>


```csharp
public CIMDictionaryRenderer Clone()
```
### DictionaryName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Gets or sets the dictionary name.</p>


```csharp
public string DictionaryName { get; set; }
```
### FieldMap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Gets or sets the field map between expected fields and actual fields.</p>


```csharp
public CIMStringMap[] FieldMap { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMDictionaryRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMDictionaryRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScalingExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns the symbol scaling ratio as a number.</p>


```csharp
public CIMExpressionInfo ScalingExpressionInfo { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDictionaryRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDictionaryRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


