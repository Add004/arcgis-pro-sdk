# CIMIPSPositioningDataServiceProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Defines the Portal Item for the IPS Positioning data service.</p>


## Object Signature

```csharp
public class CIMIPSPositioningDataServiceProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIPSPositioningDataServiceProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Defines the Portal Item for the IPS Positioning data service.</p>


```csharp
public CIMIPSPositioningDataServiceProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIPSPositioningDataServiceProperties.</p>


```csharp
public CIMIPSPositioningDataServiceProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMIPSPositioningDataServiceProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMIPSPositioningDataServiceProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### PortalItem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Gets or sets the portal item.</p>


```csharp
public CIMPortalItem PortalItem { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIPSPositioningDataServiceProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WorkspaceConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Gets or sets the workspace connection.</p>


```csharp
public CIMWorkspaceConnection WorkspaceConnection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIPSPositioningDataServiceProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


