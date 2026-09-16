# CIMGroundToGridCorrection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Defines the properties needed to perform a COGO ground to grid correction when adding new features.</p>


## Object Signature

```csharp
public class CIMGroundToGridCorrection : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroundToGridCorrection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Defines the properties needed to perform a COGO ground to grid correction when adding new features.</p>


```csharp
public CIMGroundToGridCorrection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroundToGridCorrection.</p>


```csharp
public CIMGroundToGridCorrection Clone()
```
### ConstantScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets the constant scale factor used in ground to grid calculations,
only when <xref href="ArcGIS.Core.CIM.CIMGroundToGridCorrection.ScaleType" data-throw-if-not-resolved="false"></xref> equals <xref href="ArcGIS.Core.CIM.GroundToGridScaleType.ConstantFactor" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public double ConstantScaleFactor { get; set; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets the direction angle (in degrees) that will be used in ground to grid calculations.</p>


```csharp
public double Direction { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether ground to grid corrections are currently in operation for the map.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Reconstructs the CIMGroundToGridCorrection with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroundToGridCorrection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets the type of scale that will be used in ground to grid calculations.</p>


```csharp
public GroundToGridScaleType ScaleType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroundToGridCorrection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the direction angle will be used in the ground to grid correction.</p>


```csharp
public bool UseDirection { get; set; }
```
### UseScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the distance scale will be used in the ground to grid correction.</p>


```csharp
public bool UseScale { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroundToGridCorrection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


