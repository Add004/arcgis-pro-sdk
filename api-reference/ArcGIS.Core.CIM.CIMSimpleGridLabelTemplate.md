# CIMSimpleGridLabelTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Represents a simple format for a label.</p>


## Object Signature

```csharp
public class CIMSimpleGridLabelTemplate : CIMGridLabelTemplate, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSimpleGridLabelTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Represents a simple format for a label.</p>


```csharp
public CIMSimpleGridLabelTemplate()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSimpleGridLabelTemplate.</p>


```csharp
public CIMSimpleGridLabelTemplate Clone()
```
### DynamicStringTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the dynamic text as a template for labels.</p>


```csharp
public string DynamicStringTemplate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Reconstructs the CIMSimpleGridLabelTemplate with a specified state from a JSON encoding.</p>


```csharp
public static CIMSimpleGridLabelTemplate FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the symbol for the text of labels.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSimpleGridLabelTemplate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSimpleGridLabelTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


