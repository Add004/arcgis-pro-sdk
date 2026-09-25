# CIMScale

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Represents a 2D scale or 3D Distance.</p>


## Object Signature

```csharp
public class CIMScale : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMScale()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Represents a 2D scale or 3D Distance.</p>


```csharp
public CIMScale()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Gets or sets the string value for the alias name of the Scale.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Creates a deep copy of CIMScale.</p>


```csharp
public CIMScale Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Reconstructs the CIMScale with a specified state from a JSON encoding.</p>


```csharp
public static CIMScale FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMScale and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Gets or sets the  numeric value representing the 2D scale or 3D distance.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScale.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


