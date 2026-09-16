# CIMStatisticalDataCollectionInputProperty

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Represents a property of an input feature.</p>


## Object Signature

```csharp
public class CIMStatisticalDataCollectionInputProperty : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionInputProperty()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Represents a property of an input feature.</p>


```csharp
public CIMStatisticalDataCollectionInputProperty()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Gets or sets the alias of the property.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStatisticalDataCollectionInputProperty.</p>


```csharp
public CIMStatisticalDataCollectionInputProperty Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Reconstructs the CIMStatisticalDataCollectionInputProperty with a specified state from a JSON encoding.</p>


```csharp
public static CIMStatisticalDataCollectionInputProperty FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Gets or sets the name of the property.</p>


```csharp
public string Name { get; set; }
```
### PropertyType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Gets or sets the type of the property.</p>


```csharp
public esriFieldType PropertyType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStatisticalDataCollectionInputProperty and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionInputProperty.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


