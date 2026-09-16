# CIMRepresentationRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Represents a representation renderer.</p>


## Object Signature

```csharp
public class CIMRepresentationRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRepresentationRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Represents a representation renderer.</p>


```csharp
public CIMRepresentationRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRepresentationRenderer.</p>


```csharp
public CIMRepresentationRenderer Clone()
```
### DrawInvalidRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the draw invalid rules.</p>


```csharp
public bool DrawInvalidRule { get; set; }
```
### DrawInvisibleRepresentation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the draw invisible representations.</p>


```csharp
public bool DrawInvisibleRepresentation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMRepresentationRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRepresentationRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvalidRuleColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets the invalid rule color.</p>


```csharp
public CIMColor InvalidRuleColor { get; set; }
```
### InvisibleRepresentationColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets the invisible representation color.</p>


```csharp
public CIMColor InvisibleRepresentationColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RepresentationClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets the representation class name.</p>


```csharp
public string RepresentationClassName { get; set; }
```
### RuleLegendVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets the rule legend visibility.</p>


```csharp
public int[] RuleLegendVisibility { get; set; }
```
### SymbolLayerNameMapping

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol layer name mapping.</p>


```csharp
public CIMRuleSymbolLayerNames[] SymbolLayerNameMapping { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRepresentationRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRepresentationRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


