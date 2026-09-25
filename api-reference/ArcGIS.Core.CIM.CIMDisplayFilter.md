# CIMDisplayFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Represents a display filter used to restrict the display of features across scale ranges.</p>


## Object Signature

```csharp
public class CIMDisplayFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDisplayFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Represents a display filter used to restrict the display of features across scale ranges.</p>


```csharp
public CIMDisplayFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDisplayFilter.</p>


```csharp
public CIMDisplayFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMDisplayFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMDisplayFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the maximum scale for this display filter.</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the minimum scale for this display filter.</p>


```csharp
public double MinScale { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the name of the display filter.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDisplayFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the where clause that filters features for a given scale range.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


