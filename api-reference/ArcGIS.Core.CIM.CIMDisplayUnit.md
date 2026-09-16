# CIMDisplayUnit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Represents a unit along with its display settings.</p>


## Object Signature

```csharp
public class CIMDisplayUnit : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Units set in the Pro backstage are not saved with the project unless their display settings are modified.</p>


## Members

### CIMDisplayUnit()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Represents a unit along with its display settings.</p>


```csharp
public CIMDisplayUnit()
```
### AbbreviationName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Gets or sets the abbreviation name of the unit.</p>


```csharp
public string AbbreviationName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDisplayUnit.</p>


```csharp
public CIMDisplayUnit Clone()
```
### Format

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Gets or sets the format of the unit.</p>


```csharp
public CIMNumberFormat Format { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Reconstructs the CIMDisplayUnit with a specified state from a JSON encoding.</p>


```csharp
public static CIMDisplayUnit FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Gets or sets the name of the unit.</p>


```csharp
public string Name { get; set; }
```
### PluralName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Gets or sets the plural name of the unit.</p>


```csharp
public string PluralName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDisplayUnit and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WKID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Gets or sets the WKID of the unit.</p>


```csharp
public int WKID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnit.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


