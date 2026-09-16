# CIMPointCloudBitFieldFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Represents a point cloud bit field filter.
Filters based on the bit-wise representation of the provided field. /// For a point to be retained, its attribute field bits must match /// BitsToSet and BitsToClear. Bits which are not explicitly clear nor /// set, are ignored.</p>


## Object Signature

```csharp
public class CIMPointCloudBitFieldFilter : CIMPointCloudFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudBitFieldFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Represents a point cloud bit field filter.
Filters based on the bit-wise representation of the provided field. /// For a point to be retained, its attribute field bits must match /// BitsToSet and BitsToClear. Bits which are not explicitly clear nor /// set, are ignored.</p>


```csharp
public CIMPointCloudBitFieldFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointCloudBitFieldFilter.</p>


```csharp
public CIMPointCloudBitFieldFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMPointCloudBitFieldFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointCloudBitFieldFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RequiredClearBits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Gets or sets an array of bit numbers cleared. Bit 0 is the least significant bit.</p>


```csharp
public int[] RequiredClearBits { get; set; }
```
### RequiredSetBits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Gets or sets an array of bit numbers set. Bit 0 is the least significant bit.</p>


```csharp
public int[] RequiredSetBits { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointCloudBitFieldFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudBitFieldFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


