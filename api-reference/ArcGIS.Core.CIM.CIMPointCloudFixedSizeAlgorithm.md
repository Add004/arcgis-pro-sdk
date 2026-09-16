# CIMPointCloudFixedSizeAlgorithm

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Represents a point cloud fixed size algorithm.</p>


## Object Signature

```csharp
public class CIMPointCloudFixedSizeAlgorithm : CIMPointCloudAlgorithm, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudFixedSizeAlgorithm()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Represents a point cloud fixed size algorithm.</p>


```csharp
public CIMPointCloudFixedSizeAlgorithm()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudFixedSizeAlgorithm.</p>


```csharp
public CIMPointCloudFixedSizeAlgorithm Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudFixedSizeAlgorithm with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudFixedSizeAlgorithm FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Gets or sets the size of the symbols.</p>


```csharp
public double Size { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudFixedSizeAlgorithm and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseRealWorldSymbolSizes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use real world symbols sizes (meters) vs. points.</p>


```csharp
public bool UseRealWorldSymbolSizes { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFixedSizeAlgorithm.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


