# CIMColorClassBreaksVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Represents a classified color visual variable.</p>


## Object Signature

```csharp
public class CIMColorClassBreaksVisualVariable : CIMColorVisualVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorClassBreaksVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Represents a classified color visual variable.</p>


```csharp
public CIMColorClassBreaksVisualVariable()
```
### AlwaysUpdateClassLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to automatically update class labels whenever a class upper value is changed.</p>


```csharp
public bool AlwaysUpdateClassLabels { get; set; }
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the class breaks.</p>


```csharp
public CIMClassBreak[] Breaks { get; set; }
```
### ClassBreaksLegendVisualVariableOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the legend display options.</p>


```csharp
public ClassBreaksLegendVisualVariableOptions ClassBreaksLegendVisualVariableOptions { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorClassBreaksVisualVariable.</p>


```csharp
public CIMColorClassBreaksVisualVariable Clone()
```
### ColorChannelTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating which channels of the color model will be overridden by the visual variable.</p>


```csharp
public ColorChannelTarget ColorChannelTarget { get; set; }
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the default symbol.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### DefaultSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the default symbol.</p>


```csharp
public CIMLegendPatch DefaultSymbolCustomPatch { get; set; }
```
### DefaultSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the default symbol.</p>


```csharp
public PatchShape DefaultSymbolPatch { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMColorClassBreaksVisualVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorClassBreaksVisualVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the minimum break.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowClassGaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show class gaps.</p>


```csharp
public bool ShowClassGaps { get; set; }
```
### ShowInAscendingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show classes in ascending order.</p>


```csharp
public bool ShowInAscendingOrder { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorClassBreaksVisualVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseClassBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use class breaks.</p>


```csharp
public bool UseClassBreaks { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorClassBreaksVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


