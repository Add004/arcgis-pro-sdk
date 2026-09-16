# CIMSymbolAnimationScale

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Represents the scale animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationScale : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Dynamically animates the symbol by the given scale.</p>


## Members

### CIMSymbolAnimationScale()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Represents the scale animation.</p>


```csharp
public CIMSymbolAnimationScale()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationScale.</p>


```csharp
public CIMSymbolAnimationScale Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationScale with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationScale FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Gets or sets the scale factor for the animation.</p>


```csharp
public double ScaleFactor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationScale and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationScale.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


