# CIMSymbolAnimationColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Represents the color animation.</p>


## Object Signature

```csharp
public class CIMSymbolAnimationColor : CIMSymbolAnimation, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Dynamically animates the symbol to the given color.</p>


## Members

### CIMSymbolAnimationColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Represents the color animation.</p>


```csharp
public CIMSymbolAnimationColor()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolAnimationColor.</p>


```csharp
public CIMSymbolAnimationColor Clone()
```
### ColorMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Gets or sets a value indicating how the color animation is applied.</p>


```csharp
public AnimationColorMode ColorMode { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolAnimationColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolAnimationColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Gets or sets the color to which the symbol will animate.</p>


```csharp
public CIMColor ToColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolAnimationColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolAnimationColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


