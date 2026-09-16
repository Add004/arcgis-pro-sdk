# CIMFormChoice

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Represents a single choice within a multiple choice form input.</p>


## Object Signature

```csharp
public class CIMFormChoice : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormChoice()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Represents a single choice within a multiple choice form input.</p>


```csharp
public CIMFormChoice()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormChoice.</p>


```csharp
public CIMFormChoice Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Gets or sets the label for the choice.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Reconstructs the CIMFormChoice with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormChoice FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormChoice and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Gets or sets the value stored for this choice, when selected.</p>


```csharp
public string Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormChoice.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


