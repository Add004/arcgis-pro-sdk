# CIMDirectionFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Represents a direction format.</p>


## Object Signature

```csharp
public class CIMDirectionFormat : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDirectionFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Represents a direction format.</p>


```csharp
public CIMDirectionFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDirectionFormat.</p>


```csharp
public CIMDirectionFormat Clone()
```
### DecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Gets or sets the number of decimal places to show.</p>


```csharp
public int DecimalPlaces { get; set; }
```
### DirectionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Gets or sets the direction type.</p>


```csharp
public DirectionType DirectionType { get; set; }
```
### Format

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Gets or sets the format.</p>


```csharp
public DirectionFormatOption Format { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMDirectionFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMDirectionFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDirectionFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Units

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Gets or sets the direction units.</p>


```csharp
public DirectionUnits Units { get; set; }
```
### UseNegativeAngles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use negative angles.</p>


```csharp
public bool UseNegativeAngles { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDirectionFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


