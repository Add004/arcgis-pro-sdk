# CIMSymbolAnimationSize

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Represents the size animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationSize : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Dynamically animates the symbol by the given size.</p>


## Members

### CIMSymbolAnimationSize()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Represents the size animation.</p>


```csharp
public CIMSymbolAnimationSize()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationSize.</p>


```csharp
public CIMSymbolAnimationSize Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationSize with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationSize FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationSize and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Gets or sets the size value for the animation.</p>


```csharp
public double ToSize { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationSize.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


