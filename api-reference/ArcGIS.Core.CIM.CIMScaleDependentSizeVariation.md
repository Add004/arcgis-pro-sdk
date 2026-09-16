# CIMScaleDependentSizeVariation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Represents the scale dependent size variations for a symbol reference.</p>


## Object Signature

```csharp
public class CIMScaleDependentSizeVariation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Applies to point symbols, line symbols and the outline of polygon symbols. When the symbol reference is rendered at an intermediate scale a linearly scaled size is used.</p>


## Members

### CIMScaleDependentSizeVariation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Represents the scale dependent size variations for a symbol reference.</p>


```csharp
public CIMScaleDependentSizeVariation()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMScaleDependentSizeVariation.</p>


```csharp
public CIMScaleDependentSizeVariation Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Reconstructs the CIMScaleDependentSizeVariation with a specified state from a JSON encoding.</p>


```csharp
public static CIMScaleDependentSizeVariation FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Gets or sets the scale the size is associated with.</p>


```csharp
public double Scale { get; set; }
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Gets or sets the size for the associated scale.</p>


```csharp
public double Size { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMScaleDependentSizeVariation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleDependentSizeVariation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


