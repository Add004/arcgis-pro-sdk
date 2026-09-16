# CIMUniqueValueGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Represents a unique value group.</p>


## Object Signature

```csharp
public class CIMUniqueValueGroup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMUniqueValueGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Represents a unique value group.</p>


```csharp
public CIMUniqueValueGroup()
```
### Classes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Gets or sets the classes belonging to the group.</p>


```csharp
public CIMUniqueValueClass[] Classes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMUniqueValueGroup.</p>


```csharp
public CIMUniqueValueGroup Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMUniqueValueGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMUniqueValueGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMUniqueValueGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


