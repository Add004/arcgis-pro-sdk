# CIMRasterTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Represents a raster table.</p>


## Object Signature

```csharp
public class CIMRasterTable : CIMDisplayTable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Represents a raster table.</p>


```csharp
public CIMRasterTable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterTable.</p>


```csharp
public CIMRasterTable Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Joins

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Gets or sets the joins as a data connection.</p>


```csharp
public CIMDataConnection Joins { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


