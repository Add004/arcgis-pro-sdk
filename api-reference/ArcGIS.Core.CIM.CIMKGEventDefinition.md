# CIMKGEventDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Events can be durative (with both start and end properties) or punctual (with just start or just end property).</p>


## Object Signature

```csharp
public class CIMKGEventDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGEventDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Events can be durative (with both start and end properties) or punctual (with just start or just end property).</p>


```csharp
public CIMKGEventDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGEventDefinition.</p>


```csharp
public CIMKGEventDefinition Clone()
```
### EndProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the property defining the end time of the event.</p>


```csharp
public string EndProperty { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMKGEventDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGEventDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### NamedType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Gets or sets the entity or relationship type name.</p>


```csharp
public string NamedType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartProperty

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Gets or sets the name of the property defining the start time of the event.</p>


```csharp
public string StartProperty { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGEventDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGEventDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


