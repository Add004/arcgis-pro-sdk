# CIMContourIntervalScaleBreak

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Represents a contour interval scale break.</p>


## Object Signature

```csharp
public class CIMContourIntervalScaleBreak : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMContourIntervalScaleBreak()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Represents a contour interval scale break.</p>


```csharp
public CIMContourIntervalScaleBreak()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Creates a deep copy of CIMContourIntervalScaleBreak.</p>


```csharp
public CIMContourIntervalScaleBreak Clone()
```
### ContourInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Gets or sets the contour interval.</p>


```csharp
public double ContourInterval { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Reconstructs the CIMContourIntervalScaleBreak with a specified state from a JSON encoding.</p>


```csharp
public static CIMContourIntervalScaleBreak FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMContourIntervalScaleBreak and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UpperBound

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Gets or sets the upper bound for scale break, represented as the denominator of the scale.
Values less than or equal to 0 represent infinite scale and should be used only for the final break.</p>


```csharp
public double UpperBound { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContourIntervalScaleBreak.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


