# CIMReferenceGridLabelTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Defines the label template for the reference grids.</p>


## Object Signature

```csharp
public class CIMReferenceGridLabelTemplate : CIMGridLabelTemplate, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReferenceGridLabelTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Defines the label template for the reference grids.</p>


```csharp
public CIMReferenceGridLabelTemplate()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReferenceGridLabelTemplate.</p>


```csharp
public CIMReferenceGridLabelTemplate Clone()
```
### Delimiter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the delimiter for the list of labels.</p>


```csharp
public string Delimiter { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Reconstructs the CIMReferenceGridLabelTemplate with a specified state from a JSON encoding.</p>


```csharp
public static CIMReferenceGridLabelTemplate FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the name of the label scheme.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the symbol of the label.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReferenceGridLabelTemplate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Gets or sets the list of values to label the grid.</p>


```csharp
public string[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGridLabelTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


