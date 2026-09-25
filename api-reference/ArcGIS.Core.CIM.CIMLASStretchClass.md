# CIMLASStretchClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Represents a LAS stretch class.</p>


## Object Signature

```csharp
public class CIMLASStretchClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASStretchClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Represents a LAS stretch class.</p>


```csharp
public CIMLASStretchClass()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASStretchClass.</p>


```csharp
public CIMLASStretchClass Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Reconstructs the CIMLASStretchClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASStretchClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Gets or sets the class label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASStretchClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Gets or sets the class value.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


