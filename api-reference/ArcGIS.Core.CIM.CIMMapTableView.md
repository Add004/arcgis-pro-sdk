# CIMMapTableView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Represents a map table view in the project.</p>


## Object Signature

```csharp
public class CIMMapTableView : CIMTableView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapTableView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Represents a map table view in the project.</p>


```csharp
public CIMMapTableView()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapTableView.</p>


```csharp
public CIMMapTableView Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Reconstructs the CIMMapTableView with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapTableView FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Gets or sets the path of the Map for the item in the view.</p>


```csharp
public string MapURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapTableView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapTableView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


