# CIMRasterColorCorrection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Represents a raster color correction configuration.</p>


## Object Signature

```csharp
public class CIMRasterColorCorrection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterColorCorrection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Represents a raster color correction configuration.</p>


```csharp
public CIMRasterColorCorrection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterColorCorrection.</p>


```csharp
public CIMRasterColorCorrection Clone()
```
### ColorBalanceMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the color balance method.</p>


```csharp
public ColorBalanceMethod ColorBalanceMethod { get; set; }
```
### ColorMatchingMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the color matching method.</p>


```csharp
public ColorMatchingMethod ColorMatchingMethod { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterColorCorrection with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterColorCorrection FromJson(string json, JsonDeserializationSettings settings = null)
```
### NeedContrastAdjustment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not contrast adjustment is needed.</p>


```csharp
public bool NeedContrastAdjustment { get; set; }
```
### PreStretchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the pre-stretch type of color correction.</p>


```csharp
public ColorCorrectionStretchType PreStretchType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceOID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the reference OID.</p>


```csharp
public int ReferenceOID { get; set; }
```
### TargetColorRaster

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the target color raster.</p>


```csharp
public CIMDataConnection TargetColorRaster { get; set; }
```
### TargetColorSurfaceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets the target color surface type.</p>


```csharp
public TargetColorSurfaceType TargetColorSurfaceType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterColorCorrection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UserDefinedReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a user defined reference.</p>


```csharp
public bool UserDefinedReference { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterColorCorrection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


