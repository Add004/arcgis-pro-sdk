# CIMSymbolAnimationRotation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Represents the rotation animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationRotation : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Dynamically animates the symbol to the given rotation value.</p>


## Members

### CIMSymbolAnimationRotation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Represents the rotation animation.</p>


```csharp
public CIMSymbolAnimationRotation()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationRotation.</p>


```csharp
public CIMSymbolAnimationRotation Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationRotation with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationRotation FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotateClockwise

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the rotation animation is applied clockwise or counterclockwise.</p>


```csharp
public bool RotateClockwise { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationRotation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToRotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Gets or sets the rotation value to which the symbol will animate.</p>


```csharp
public double ToRotation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationRotation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


