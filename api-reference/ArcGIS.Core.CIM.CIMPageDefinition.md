# CIMPageDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Represents page definition.</p>


## Object Signature

```csharp
public class CIMPageDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPageDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Represents page definition.</p>


```csharp
public CIMPageDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPageDefinition.</p>


```csharp
public CIMPageDefinition Clone()
```
### ExcludePages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to exclude pages. Specify false to show features that match or true to show features that don't match.</p>


```csharp
public bool ExcludePages { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMPageDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMPageDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### PageFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Gets or sets the page field name. Show features where the value of this field either matches or doesn't match the current map series page name. Match versus don't match is controlled by ExcludePages.</p>


```csharp
public string PageFieldName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPageDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPageDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


