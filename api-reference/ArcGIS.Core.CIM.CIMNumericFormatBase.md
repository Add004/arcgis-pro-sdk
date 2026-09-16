# CIMNumericFormatBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Represents the numeric format base class.</p>


## Object Signature

```csharp
public abstract class CIMNumericFormatBase : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNumericFormatBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Creates a default CIMNumericFormatBase.</p>


```csharp
public CIMNumericFormatBase()
```
### AlignmentOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets the alignment option.</p>


```csharp
public esriNumericAlignmentEnum AlignmentOption { get; set; }
```
### AlignmentWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets the alignment width.</p>


```csharp
public int AlignmentWidth { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RoundingOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets the rounding option.</p>


```csharp
public esriRoundingOptionEnum RoundingOption { get; set; }
```
### RoundingValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets the rounding value, whose meaning depends on the rounding option.</p>


```csharp
public int RoundingValue { get; set; }
```
### ShowPlusSign

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether formatted numbers contain a plus sign for positive numbers.</p>


```csharp
public bool ShowPlusSign { get; set; }
```
### UseSeparator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether formatted numbers contain digit grouping symbols.</p>


```csharp
public bool UseSeparator { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZeroPad

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNumericFormatBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether formatted numbers contain padded zeros to the right of the decimal.</p>


```csharp
public bool ZeroPad { get; set; }
```


