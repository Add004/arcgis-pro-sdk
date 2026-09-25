# CIMMaplexLabelStackingProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Represents Maplex label stacking properties.</p>


## Object Signature

```csharp
public class CIMMaplexLabelStackingProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexLabelStackingProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Represents Maplex label stacking properties.</p>


```csharp
public CIMMaplexLabelStackingProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexLabelStackingProperties.</p>


```csharp
public CIMMaplexLabelStackingProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexLabelStackingProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexLabelStackingProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumNumberOfCharsPerLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum number of characters per line.</p>


```csharp
public int MaximumNumberOfCharsPerLine { get; set; }
```
### MaximumNumberOfLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum number of lines.</p>


```csharp
public int MaximumNumberOfLines { get; set; }
```
### MinimumNumberOfCharsPerLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum number of characters per line.</p>


```csharp
public int MinimumNumberOfCharsPerLine { get; set; }
```
### PreferToStackLongLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to prefer to stack long labels.</p>


```csharp
public bool PreferToStackLongLabels { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Separators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets the stacking separators.</p>


```csharp
public CIMMaplexStackingSeparator[] Separators { get; set; }
```
### StackAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets the stacking alignment.</p>


```csharp
public MaplexStackingAlignment StackAlignment { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexLabelStackingProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrimStackingSeparators

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether leading and trailing stacking separators are trimmed from the label string.</p>


```csharp
public bool TrimStackingSeparators { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexLabelStackingProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


