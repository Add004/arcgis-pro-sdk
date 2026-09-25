# CIMReferenceGrid

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Defines a reference grid.</p>


## Object Signature

```csharp
public class CIMReferenceGrid : CIMMapGrid, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMReferenceGrid()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Defines a reference grid.</p>


```csharp
public CIMReferenceGrid()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Creates a deep copy of CIMReferenceGrid.</p>


```csharp
public CIMReferenceGrid Clone()
```
### ColumnCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Gets or sets the number of columns for the reference grids.</p>


```csharp
public int ColumnCount { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Reconstructs the CIMReferenceGrid with a specified state from a JSON encoding.</p>


```csharp
public static CIMReferenceGrid FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLines

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Gets or sets the collection of the grid lines.</p>


```csharp
public CIMGridLine[] GridLines { get; set; }
```
### IsAutoScaled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to auto-adjust the grid according to the size of the map frame.</p>


```csharp
public bool IsAutoScaled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RowCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Gets or sets the number of rows for the reference grids.</p>


```csharp
public int RowCount { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMReferenceGrid and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMReferenceGrid.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


