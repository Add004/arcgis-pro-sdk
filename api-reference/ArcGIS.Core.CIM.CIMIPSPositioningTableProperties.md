# CIMIPSPositioningTableProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Defines the URI and selected global ID for the IPS positioning table.</p>


## Object Signature

```csharp
[Obsolete("CIMIPSPositioningTableProperties is deprecated at 3.3. ")]
public class CIMIPSPositioningTableProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSPositioningTableProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Defines the URI and selected global ID for the IPS positioning table.</p>


```csharp
public CIMIPSPositioningTableProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSPositioningTableProperties.</p>


```csharp
public CIMIPSPositioningTableProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSPositioningTableProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSPositioningTableProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectedGlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Gets or sets the global ID of the row selected from the IPS positioning table.</p>


```csharp
public string SelectedGlobalID { get; set; }
```
### TableURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Gets or sets the URI for the IPS positioning table in the map.</p>


```csharp
public string TableURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSPositioningTableProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningTableProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


