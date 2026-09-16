# CIMVerticalLegendItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Represents a vertical legend item in a legend.</p>


## Object Signature

```csharp
public class CIMVerticalLegendItem : CIMLegendItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVerticalLegendItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Represents a vertical legend item in a legend.</p>


```csharp
public CIMVerticalLegendItem()
```
### Arrangement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Gets or sets the Arrangement.</p>


```csharp
public LegendItemArrangement Arrangement { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVerticalLegendItem.</p>


```csharp
public CIMVerticalLegendItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Reconstructs the CIMVerticalLegendItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMVerticalLegendItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### PatchAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Gets or sets a value to allow alignment of graduated symbols to be specified.</p>


```csharp
public HorizontalAlignment PatchAlignment { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVerticalLegendItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVerticalLegendItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


