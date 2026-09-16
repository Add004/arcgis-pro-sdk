# CIMAreaLegendPatch

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Represents an area legend patch, small rectangles used to display legend classes.</p>


## Object Signature

```csharp
public class CIMAreaLegendPatch : CIMLegendPatch, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAreaLegendPatch()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Represents an area legend patch, small rectangles used to display legend classes.</p>


```csharp
public CIMAreaLegendPatch()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAreaLegendPatch.</p>


```csharp
public CIMAreaLegendPatch Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Reconstructs the CIMAreaLegendPatch with a specified state from a JSON encoding.</p>


```csharp
public static CIMAreaLegendPatch FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAreaLegendPatch and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAreaLegendPatch.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


