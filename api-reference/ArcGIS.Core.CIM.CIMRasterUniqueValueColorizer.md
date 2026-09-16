# CIMRasterUniqueValueColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Represents a raster unique value colorizer.</p>


## Object Signature

```csharp
public class CIMRasterUniqueValueColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterUniqueValueColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Represents a raster unique value colorizer.</p>


```csharp
public CIMRasterUniqueValueColorizer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterUniqueValueColorizer.</p>


```csharp
public CIMRasterUniqueValueColorizer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DefaultColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the default color.</p>


```csharp
public CIMColor DefaultColor { get; set; }
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the field name to render.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterUniqueValueColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterUniqueValueColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Groups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the unique value groups.</p>


```csharp
public CIMRasterUniqueValueGroup[] Groups { get; set; }
```
### IsDefaultColorVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the default color visibility is shown in the contents pane.</p>


```csharp
public bool IsDefaultColorVisible { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets the number format applied to values for display.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowClassVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the class visibility is shown in the contents pane.</p>


```csharp
public bool ShowClassVisibility { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterUniqueValueColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDefaultColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default color.</p>


```csharp
public bool UseDefaultColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


