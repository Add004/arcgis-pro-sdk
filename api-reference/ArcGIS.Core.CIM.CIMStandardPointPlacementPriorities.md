# CIMStandardPointPlacementPriorities

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Represents standard label engine point placement priorities.</p>


## Object Signature

```csharp
public class CIMStandardPointPlacementPriorities : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandardPointPlacementPriorities()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Represents standard label engine point placement priorities.</p>


```csharp
public CIMStandardPointPlacementPriorities()
```
### AboveCenter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the above center position.</p>


```csharp
public int AboveCenter { get; set; }
```
### AboveLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the above left position.</p>


```csharp
public int AboveLeft { get; set; }
```
### AboveRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the above right position.</p>


```csharp
public int AboveRight { get; set; }
```
### BelowCenter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the below center position.</p>


```csharp
public int BelowCenter { get; set; }
```
### BelowLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the below left position.</p>


```csharp
public int BelowLeft { get; set; }
```
### BelowRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the below right position.</p>


```csharp
public int BelowRight { get; set; }
```
### CenterLeft

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the center left position.</p>


```csharp
public int CenterLeft { get; set; }
```
### CenterRight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Gets or sets the label position priority for the center right position.</p>


```csharp
public int CenterRight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandardPointPlacementPriorities.</p>


```csharp
public CIMStandardPointPlacementPriorities Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Reconstructs the CIMStandardPointPlacementPriorities with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandardPointPlacementPriorities FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandardPointPlacementPriorities and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardPointPlacementPriorities.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


