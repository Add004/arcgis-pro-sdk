# CIMLinearContinuousColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Represents a linear continuous color ramp scheme.</p>


## Object Signature

```csharp
public class CIMLinearContinuousColorRamp : CIMContinuousColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">A color ramp color scheme that has a linear transition between two colors. This ramp is created using the CIELAB algorithm which blends two colors without traversing the intervening hue space.</p>


## Members

### CIMLinearContinuousColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Represents a linear continuous color ramp scheme.</p>


```csharp
public CIMLinearContinuousColorRamp()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinearContinuousColorRamp.</p>


```csharp
public CIMLinearContinuousColorRamp Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Reconstructs the CIMLinearContinuousColorRamp with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinearContinuousColorRamp FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinearContinuousColorRamp and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinearContinuousColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


