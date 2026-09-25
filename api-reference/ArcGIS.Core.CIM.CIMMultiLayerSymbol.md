# CIMMultiLayerSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Represents a multilayer symbol, a generic type for point, line, and polygon symbols, specifying that they can contain more than one symbol layers.</p>


## Object Signature

```csharp
public abstract class CIMMultiLayerSymbol : CIMSymbol, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultiLayerSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Represents a multilayer symbol, a generic type for point, line, and polygon symbols, specifying that they can contain more than one symbol layers.</p>


```csharp
protected CIMMultiLayerSymbol()
```
### Animations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Gets or sets the animations that are applied to the symbol.</p>


```csharp
public CIMSymbolAnimation[] Animations { get; set; }
```
### Effects

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Gets or sets the geometric effects that are applied to the symbol.</p>


```csharp
public CIMGeometricEffect[] Effects { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Gets or sets the symbol layers. Symbol layers are the components that make up a symbol. A symbol layer is represented by a stroke, fill, marker, or procedural symbol layer.</p>


```csharp
public CIMSymbolLayer[] SymbolLayers { get; set; }
```
### ThumbnailURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Gets or sets the representative image of the symbol as a base64 encoded string.</p>


```csharp
public string ThumbnailURI { get; set; }
```
### UseRealWorldSymbolSizes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the symbol size properties are rendered using real world units or page units. When set to true the symbol will draw using real world units (e.g. meters).</p>


```csharp
public bool UseRealWorldSymbolSizes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiLayerSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


