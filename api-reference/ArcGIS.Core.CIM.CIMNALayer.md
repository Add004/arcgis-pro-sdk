# CIMNALayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Represents a network analysis layer.</p>


## Object Signature

```csharp
public class CIMNALayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNALayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Represents a network analysis layer.</p>


```csharp
public CIMNALayer()
```
### Agents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the agents.</p>


```csharp
public NAAgent[] Agents { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNALayer.</p>


```csharp
public CIMNALayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNALayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNALayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the layer URIs of the layers in the group layer.</p>


```csharp
public string[] Layers { get; set; }
```
### Locator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the locator.</p>


```csharp
public NALocatorDefinition Locator { get; set; }
```
### LocatorOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the locator overrides.</p>


```csharp
public CIMNALocatorOverrideClass[] LocatorOverrides { get; set; }
```
### NAWorkspace

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets data connection for the NA workspace.</p>


```csharp
public CIMDataConnection NAWorkspace { get; set; }
```
### NetworkDataset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets data connection for the network dataset.</p>


```csharp
public CIMDataConnection NetworkDataset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Solver

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the NA solver.</p>


```csharp
public NASolverDefinition Solver { get; set; }
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### SymbolLayerDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Gets or sets the symbol layer drawing definition.</p>


```csharp
public CIMSymbolLayerDrawing SymbolLayerDrawing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNALayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


