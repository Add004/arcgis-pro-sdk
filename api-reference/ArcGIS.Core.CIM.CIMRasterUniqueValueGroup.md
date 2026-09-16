# CIMRasterUniqueValueGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Represents a raster unique value group.</p>


## Object Signature

```csharp
public class CIMRasterUniqueValueGroup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterUniqueValueGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Represents a raster unique value group.</p>


```csharp
public CIMRasterUniqueValueGroup()
```
### Classes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Gets or sets an array of classes making up the group.</p>


```csharp
public CIMRasterUniqueValueClass[] Classes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterUniqueValueGroup.</p>


```csharp
public CIMRasterUniqueValueGroup Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterUniqueValueGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterUniqueValueGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Gets or sets the group heading.</p>


```csharp
public string Heading { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterUniqueValueGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterUniqueValueGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


