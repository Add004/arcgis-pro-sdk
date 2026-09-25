# CIMTraversableDirectionsAdornerPointSymbolClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Traversable directions, label, and adorner point symbol.
The applicable adorner point symbol is oriented and added to the restriction status symbol when drawn to indicate the directional traversability of network elements.</p>


## Object Signature

```csharp
public class CIMTraversableDirectionsAdornerPointSymbolClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTraversableDirectionsAdornerPointSymbolClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Traversable directions, label, and adorner point symbol.
The applicable adorner point symbol is oriented and added to the restriction status symbol when drawn to indicate the directional traversability of network elements.</p>


```csharp
public CIMTraversableDirectionsAdornerPointSymbolClass()
```
### AdornerPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the adorner point symbol to be composed with the restriction status symbol when drawn.</p>


```csharp
public CIMSymbolReference AdornerPointSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTraversableDirectionsAdornerPointSymbolClass.</p>


```csharp
public CIMTraversableDirectionsAdornerPointSymbolClass Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Reconstructs the CIMTraversableDirectionsAdornerPointSymbolClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMTraversableDirectionsAdornerPointSymbolClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTraversableDirectionsAdornerPointSymbolClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TraversableDirections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the supported traversable directions represented by the adorner point symbol.</p>


```csharp
public TraversableDirections TraversableDirections { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTraversableDirectionsAdornerPointSymbolClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


