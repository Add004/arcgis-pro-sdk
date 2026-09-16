# CIMGeotriggerFenceParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Represents the parameters of a geotrigger fence.</p>


## Object Signature

```csharp
public class CIMGeotriggerFenceParameters : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotriggerFenceParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Represents the parameters of a geotrigger fence.</p>


```csharp
public CIMGeotriggerFenceParameters()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotriggerFenceParameters.</p>


```csharp
public CIMGeotriggerFenceParameters Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotriggerFenceParameters with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotriggerFenceParameters FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotriggerFenceParameters and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceParameters.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


