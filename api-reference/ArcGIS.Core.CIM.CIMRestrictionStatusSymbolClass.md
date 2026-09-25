# CIMRestrictionStatusSymbolClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Restriction status, label, and symbol.</p>


## Object Signature

```csharp
public class CIMRestrictionStatusSymbolClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRestrictionStatusSymbolClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Restriction status, label, and symbol.</p>


```csharp
public CIMRestrictionStatusSymbolClass()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRestrictionStatusSymbolClass.</p>


```csharp
public CIMRestrictionStatusSymbolClass Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Reconstructs the CIMRestrictionStatusSymbolClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMRestrictionStatusSymbolClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Status

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the restriction status represented by the symbol.</p>


```csharp
public RestrictionStatus Status { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRestrictionStatusSymbolClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRestrictionStatusSymbolClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


