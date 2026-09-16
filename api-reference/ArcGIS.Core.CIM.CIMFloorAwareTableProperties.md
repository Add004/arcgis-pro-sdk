# CIMFloorAwareTableProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Represents floor-aware properties for the layer/table used in floor filtering.</p>


## Object Signature

```csharp
public class CIMFloorAwareTableProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloorAwareTableProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Represents floor-aware properties for the layer/table used in floor filtering.</p>


```csharp
public CIMFloorAwareTableProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloorAwareTableProperties.</p>


```csharp
public CIMFloorAwareTableProperties Clone()
```
### FloorField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Gets or sets the name of the field that carries the floor value used for floor filtering.</p>


```csharp
public string FloorField { get; set; }
```
### FloorFilterRank

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Gets or sets rank or &quot;level&quot; at which the layer/table participates in filtering for Indoors or floor-aware layers/tables.</p>


```csharp
public FloorFilterRank FloorFilterRank { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMFloorAwareTableProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloorAwareTableProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloorAwareTableProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZFiltering

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloorAwareTableProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether Z value floor filtering will be used.</p>


```csharp
public bool ZFiltering { get; set; }
```


