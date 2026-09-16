# CIMClassBreaksRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Represents a class break renderer.</p>


## Object Signature

```csharp
public class CIMClassBreaksRenderer : CIMClassBreaksRendererBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMClassBreaksRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Represents a class break renderer.</p>


```csharp
public CIMClassBreaksRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMClassBreaksRenderer.</p>


```csharp
public CIMClassBreaksRenderer Clone()
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion clause.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion description.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion label.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion symbol.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### ExclusionSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the exclusion symbol.</p>


```csharp
public CIMLegendPatch ExclusionSymbolCustomPatch { get; set; }
```
### ExclusionSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the exclusion symbol.</p>


```csharp
public PatchShape ExclusionSymbolPatch { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMClassBreaksRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMClassBreaksRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization type.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMClassBreaksRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the exclusion symbol.</p>


```csharp
public bool UseExclusionSymbol { get; set; }
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Gets or sets the visual variables.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


