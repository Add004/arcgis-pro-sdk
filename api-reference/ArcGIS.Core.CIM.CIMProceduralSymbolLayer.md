# CIMProceduralSymbolLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Represents a procedural symbol layer which defines rendering using script-based logic to construct complex 3D objects and textures from simple geometries. Properties of the symbol are derived from a rule package (.rpk file).</p>


## Object Signature

```csharp
public class CIMProceduralSymbolLayer : CIMSymbolLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProceduralSymbolLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Represents a procedural symbol layer which defines rendering using script-based logic to construct complex 3D objects and textures from simple geometries. Properties of the symbol are derived from a rule package (.rpk file).</p>


```csharp
public CIMProceduralSymbolLayer()
```
### Attributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol attributes as specified by the CGA code in the rule package.</p>


```csharp
public CIMCGAAttribute[] Attributes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProceduralSymbolLayer.</p>


```csharp
public CIMProceduralSymbolLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMProceduralSymbolLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMProceduralSymbolLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RulePackage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the referenced rule package file.</p>


```csharp
public string RulePackage { get; set; }
```
### RulePackageName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Gets or sets the name of the package displayed in the user interface.</p>


```csharp
public string RulePackageName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProceduralSymbolLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProceduralSymbolLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


