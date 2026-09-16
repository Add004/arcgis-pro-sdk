# CIMGeotriggerFeatureFenceParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Represents the parameters of a geotrigger feature fence.</p>


## Object Signature

```csharp
public class CIMGeotriggerFeatureFenceParameters : CIMGeotriggerFenceParameters, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotriggerFeatureFenceParameters()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Represents the parameters of a geotrigger feature fence.</p>


```csharp
public CIMGeotriggerFeatureFenceParameters()
```
### BufferDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Gets or sets the buffer distance (in meters) to apply to fence features.</p>


```csharp
public double BufferDistance { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotriggerFeatureFenceParameters.</p>


```csharp
public CIMGeotriggerFeatureFenceParameters Clone()
```
### Filter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Gets or sets the filter that should be used for the fence.</p>


```csharp
public CIMGeotriggerFenceFilter Filter { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotriggerFeatureFenceParameters with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotriggerFeatureFenceParameters FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Gets or sets source data connection for the fence features.</p>


```csharp
public CIMDataConnection SourceDataConnection { get; set; }
```
### SourceLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Gets or sets source layer URI for the fence features.</p>


```csharp
public string SourceLayer { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotriggerFeatureFenceParameters and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFeatureFenceParameters.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


