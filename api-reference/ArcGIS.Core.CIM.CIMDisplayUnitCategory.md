# CIMDisplayUnitCategory

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Represents a category of display units.</p>


## Object Signature

```csharp
public class CIMDisplayUnitCategory : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDisplayUnitCategory()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Represents a category of display units.</p>


```csharp
public CIMDisplayUnitCategory()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDisplayUnitCategory.</p>


```csharp
public CIMDisplayUnitCategory Clone()
```
### DefaultUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Gets or sets the WKID of the default unit for the category.</p>


```csharp
public int DefaultUnit { get; set; }
```
### ExcludedUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Gets or sets the WKIDs of units that have been removed from the category.</p>


```csharp
public int[] ExcludedUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Reconstructs the CIMDisplayUnitCategory with a specified state from a JSON encoding.</p>


```csharp
public static CIMDisplayUnitCategory FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDisplayUnitCategory and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnitOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Gets or sets the overridden display settings for units in the category.</p>


```csharp
public CIMDisplayUnit[] UnitOverrides { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitCategory.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


