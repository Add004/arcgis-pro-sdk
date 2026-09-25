# CIMPopupUtilityNetworkAssociation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Represents pop-up utility network association.</p>


## Object Signature

```csharp
public class CIMPopupUtilityNetworkAssociation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPopupUtilityNetworkAssociation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Represents pop-up utility network association.</p>


```csharp
public CIMPopupUtilityNetworkAssociation()
```
### AssociatedAssetGroupID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the associated asset group id.</p>


```csharp
public long AssociatedAssetGroupID { get; set; }
```
### AssociatedAssetTypeID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the associated asset type id.</p>


```csharp
public long AssociatedAssetTypeID { get; set; }
```
### AssociatedNetworkSourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the associated network source id.</p>


```csharp
public long AssociatedNetworkSourceID { get; set; }
```
### AssociationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public PopupUtilityNetworkAssociationType AssociationType { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the association type.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPopupUtilityNetworkAssociation.</p>


```csharp
public CIMPopupUtilityNetworkAssociation Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Reconstructs the CIMPopupUtilityNetworkAssociation with a specified state from a JSON encoding.</p>


```csharp
public static CIMPopupUtilityNetworkAssociation FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPopupUtilityNetworkAssociation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupUtilityNetworkAssociation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


