# CIMUtilityNetworkAssociationsMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Represents utility network associations media info.</p>


## Object Signature

```csharp
public class CIMUtilityNetworkAssociationsMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMUtilityNetworkAssociationsMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Represents utility network associations media info.</p>


```csharp
public CIMUtilityNetworkAssociationsMediaInfo()
```
### Associations

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the array of utility network associations.</p>


```csharp
public CIMPopupUtilityNetworkAssociation[] Associations { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMUtilityNetworkAssociationsMediaInfo.</p>


```csharp
public CIMUtilityNetworkAssociationsMediaInfo Clone()
```
### DisplayCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum number of features to display per layer.</p>


```csharp
public int DisplayCount { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMUtilityNetworkAssociationsMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMUtilityNetworkAssociationsMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMUtilityNetworkAssociationsMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUtilityNetworkAssociationsMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


