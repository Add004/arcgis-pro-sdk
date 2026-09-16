# CIMSymbolAnimationTransparency

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Represents the transparency animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationTransparency : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Dynamically animates the symbol to the given transparency.</p>


## Members

### CIMSymbolAnimationTransparency()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Represents the transparency animation.</p>


```csharp
public CIMSymbolAnimationTransparency()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationTransparency.</p>


```csharp
public CIMSymbolAnimationTransparency Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationTransparency with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationTransparency FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationTransparency and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToTransparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Gets or sets the transparency to which the symbol will animate.</p>


```csharp
public double ToTransparency { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationTransparency.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


