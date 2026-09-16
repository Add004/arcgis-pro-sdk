# CIMMaplexStrategyPriorities

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Represents Maplex strategy priorities.</p>


## Object Signature

```csharp
public class CIMMaplexStrategyPriorities : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexStrategyPriorities()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Represents Maplex strategy priorities.</p>


```csharp
public CIMMaplexStrategyPriorities()
```
### Abbreviation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Gets or sets the priority for abbreviation.</p>


```csharp
public int Abbreviation { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexStrategyPriorities.</p>


```csharp
public CIMMaplexStrategyPriorities Clone()
```
### FontCompression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Gets or sets the priority for font compression.</p>


```csharp
public int FontCompression { get; set; }
```
### FontReduction

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Gets or sets the priority for font reduction.</p>


```csharp
public int FontReduction { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexStrategyPriorities with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexStrategyPriorities FromJson(string json, JsonDeserializationSettings settings = null)
```
### Overrun

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Gets or sets the priority for overrun.</p>


```csharp
public int Overrun { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Stacking

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Gets or sets the priority for stacking.</p>


```csharp
public int Stacking { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexStrategyPriorities and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexStrategyPriorities.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


