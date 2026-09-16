# CIMPortalItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Represents a reference to a portal item.</p>


## Object Signature

```csharp
public class CIMPortalItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPortalItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Represents a reference to a portal item.</p>


```csharp
public CIMPortalItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPortalItem.</p>


```csharp
public CIMPortalItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Reconstructs the CIMPortalItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMPortalItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### ItemID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Gets or sets the ID of the portal Item.</p>


```csharp
public string ItemID { get; set; }
```
### PortalURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Gets or sets the portal URL of the item.</p>


```csharp
public string PortalURL { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPortalItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPortalItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


