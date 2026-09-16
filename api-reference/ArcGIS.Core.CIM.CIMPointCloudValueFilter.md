# CIMPointCloudValueFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Represents a point cloud value filter.
Filter points based on the value of an specified attribute.</p>


## Object Signature

```csharp
public class CIMPointCloudValueFilter : CIMPointCloudFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudValueFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Represents a point cloud value filter.
Filter points based on the value of an specified attribute.</p>


```csharp
public CIMPointCloudValueFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudValueFilter.</p>


```csharp
public CIMPointCloudValueFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudValueFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudValueFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Gets or sets the mode that determines if the ValueList is an include list or an exclude list.</p>


```csharp
public PointCloudValueFilterMode Mode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudValueFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Gets or sets the values used as exclude or include list.</p>


```csharp
public double[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudValueFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


