# CIMNitfFeatureSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Represents NITF feature sub layer.</p>


## Object Signature

```csharp
public class CIMNitfFeatureSubLayer : CIMFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMNitfFeatureSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Represents NITF feature sub layer.</p>


```csharp
public CIMNitfFeatureSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNitfFeatureSubLayer.</p>


```csharp
public CIMNitfFeatureSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNitfFeatureSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNitfFeatureSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNitfFeatureSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfFeatureSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


