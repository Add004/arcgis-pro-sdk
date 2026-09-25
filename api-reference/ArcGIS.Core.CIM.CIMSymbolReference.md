# CIMSymbolReference

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Represents a symbol reference.</p>


## Object Signature

```csharp
public class CIMSymbolReference : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Symbol references currently store the symbol in-line in the symbol property. Overrides here are used primarily by renderers to pass overrides through the drawing pipeline.</p>


## Members

### CIMSymbolReference()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Represents a symbol reference.</p>


```csharp
public CIMSymbolReference()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolReference.</p>


```csharp
public CIMSymbolReference Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolReference with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolReference FromJson(string json, JsonDeserializationSettings settings = null)
```
### GetSymbol(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Returns a symbol from an XML encoding of a CIMSymbol.</p>


```csharp
public static CIMSymbol GetSymbol(string symbolXml)
```
### MaxDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the maximum distance at which symbols are visible. Objects beyond this point don't get rendered.</p>


```csharp
public double MaxDistance { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the maximum scale range the symbol reference should be displayed at.</p>


```csharp
public double MaxScale { get; set; }
```
### MinDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the minimum distance at which symbols are visible. Objects closer than this don't get rendered.</p>


```csharp
public double MinDistance { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the minimum scale range the symbol reference should be displayed at.</p>


```csharp
public double MinScale { get; set; }
```
### PrimitiveOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the primitive overrides. Typically set by renderers at draw time.</p>


```csharp
public CIMPrimitiveOverride[] PrimitiveOverrides { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleDependentSizeVariation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets an array of scale dependent sizes.</p>


```csharp
public CIMScaleDependentSizeVariation[] ScaleDependentSizeVariation { get; set; }
```
### SetSymbol(ref CIMSymbolReference, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Sets a symbol on a symbol reference from an XML encoding of the symbol.</p>


```csharp
public static bool SetSymbol(ref CIMSymbolReference symbolRef, string symbolXml)
```
### StylePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the style path. Reserved for future use.</p>


```csharp
public string StylePath { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbol Symbol { get; set; }
```
### SymbolName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Gets or sets the symbol name.</p>


```csharp
public string SymbolName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolReference and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolReference.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


