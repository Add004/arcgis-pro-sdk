# CIMKGDurativeEventsDurationConstraint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Constraints on the duration of durative events.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="3">Note that this constraint does not apply to punctual events.</p>


## Object Signature

```csharp
public class CIMKGDurativeEventsDurationConstraint : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGDurativeEventsDurationConstraint()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Constraints on the duration of durative events.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="3">Note that this constraint does not apply to punctual events.</p>


```csharp
public CIMKGDurativeEventsDurationConstraint()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGDurativeEventsDurationConstraint.</p>


```csharp
public CIMKGDurativeEventsDurationConstraint Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Reconstructs the CIMKGDurativeEventsDurationConstraint with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGDurativeEventsDurationConstraint FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Gets or sets the maximum duration. The unit of maximum duration is TimeUnit.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="3">This value is only used if UseMaxDuration is true.</p>


```csharp
public double MaxDuration { get; set; }
```
### MinDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Gets or sets the minimum duration. The unit of minimum duration is TimeUnit.</p>


```csharp
public double MinDuration { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Gets or sets the unit of minimum and maximum durations.</p>
<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="3">Accepted values are {
esriTimeUnitsMilliseconds,
esriTimeUnitsSeconds,
esriTimeUnitsMinutes,
esriTimeUnitsHours,
esriTimeUnitsDays,
esriTimeUnitsWeeks }.</p>


```csharp
public esriTimeUnits TimeUnit { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGDurativeEventsDurationConstraint and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseMaxDuration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the maximum duration should be used.</p>


```csharp
public bool UseMaxDuration { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDurativeEventsDurationConstraint.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


