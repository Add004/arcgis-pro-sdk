# CIMDataEngineeringStatisticColumn

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Provide access to the statistic column.</p>


## Object Signature

```csharp
public class CIMDataEngineeringStatisticColumn : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDataEngineeringStatisticColumn()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Provide access to the statistic column.</p>


```csharp
public CIMDataEngineeringStatisticColumn()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDataEngineeringStatisticColumn.</p>


```csharp
public CIMDataEngineeringStatisticColumn Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Reconstructs the CIMDataEngineeringStatisticColumn with a specified state from a JSON encoding.</p>


```csharp
public static CIMDataEngineeringStatisticColumn FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsFrozen

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the column is frozen.</p>


```csharp
public bool IsFrozen { get; set; }
```
### IsSorted

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the column is sorted.</p>


```csharp
public bool IsSorted { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the column is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Gets or sets the column name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SortDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Gets or sets a value indicating the sort direction.</p>


```csharp
public SortOrderType SortDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDataEngineeringStatisticColumn and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringStatisticColumn.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


