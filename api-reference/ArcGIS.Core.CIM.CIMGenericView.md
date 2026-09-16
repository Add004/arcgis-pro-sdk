# CIMGenericView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Represents a generic view.</p>


## Object Signature

```csharp
public class CIMGenericView : CIMView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGenericView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Represents a generic view.</p>


```csharp
public CIMGenericView()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGenericView.</p>


```csharp
public CIMGenericView Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Reconstructs the CIMGenericView with a specified state from a JSON encoding.</p>


```csharp
public static CIMGenericView FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGenericView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ViewProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Gets or sets a property set containing properties of the generic view in the project.</p>


```csharp
public IDictionary<string, object> ViewProperties { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGenericView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


