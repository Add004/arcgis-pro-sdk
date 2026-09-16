# CIMIPSAwareMapProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Define the properties needed to identify IPS layer and table.</p>


## Object Signature

```csharp
public class CIMIPSAwareMapProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSAwareMapProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Define the properties needed to identify IPS layer and table.</p>


```csharp
public CIMIPSAwareMapProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSAwareMapProperties.</p>


```csharp
public CIMIPSAwareMapProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSAwareMapProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSAwareMapProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### IPSConfiguration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the IPS configuration.</p>


```csharp
public CIMIPSConfiguration IPSConfiguration { get; set; }
```
### IPSPositioningDataServiceProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the IPS positioning data service from a portal.</p>


```csharp
public CIMIPSPositioningDataServiceProperties IPSPositioningDataServiceProperties { get; set; }
```
### IPSPositioningTableProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the IPS positioning table in the map.</p>


```csharp
[Obsolete("IPSPositioningTableProperties is deprecated at 3.3. Use IPSPositioningDataServiceProperties instead")]
public CIMIPSPositioningTableProperties IPSPositioningTableProperties { get; set; }
```
### IPSRecordingsLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the IPS recordings layer in the map.</p>


```csharp
public string IPSRecordingsLayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSAwareMapProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSAwareMapProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


