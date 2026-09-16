# CIMProportionalPieSizeOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Represents proportional pie size options.</p>


## Object Signature

```csharp
public class CIMProportionalPieSizeOptions : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProportionalPieSizeOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Represents proportional pie size options.</p>


```csharp
public CIMProportionalPieSizeOptions()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProportionalPieSizeOptions.</p>


```csharp
public CIMProportionalPieSizeOptions Clone()
```
### FlanneryCompensation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use Flannery compensation.</p>


```csharp
public bool FlanneryCompensation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Reconstructs the CIMProportionalPieSizeOptions with a specified state from a JSON encoding.</p>


```csharp
public static CIMProportionalPieSizeOptions FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the maximum size.</p>


```csharp
public double MaximumSize { get; set; }
```
### MaximumValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the data value that corresponds to the maximum size.</p>


```csharp
public double MaximumValue { get; set; }
```
### MinimumSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the minimum size.</p>


```csharp
public double MinimumSize { get; set; }
```
### MinimumValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the data value that corresponds to the minimum size.</p>


```csharp
public double MinimumValue { get; set; }
```
### ProportionalBySum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to size the pie chart proportionally by the sum of field values.</p>


```csharp
public bool ProportionalBySum { get; set; }
```
### ProportionalExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the Arcade expression that is used to size the pie chart proportionally.</p>


```csharp
public CIMExpressionInfo ProportionalExpressionInfo { get; set; }
```
### ProportionalFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Gets or sets the field that is used to size the pie chart proportionally.</p>


```csharp
public string ProportionalFieldName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProportionalPieSizeOptions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalPieSizeOptions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


