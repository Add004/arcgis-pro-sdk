# CIMDefinitionFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Contains filters so that only features satisfying these definitions will be displayed.</p>


## Object Signature

```csharp
public class CIMDefinitionFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDefinitionFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Contains filters so that only features satisfying these definitions will be displayed.</p>


```csharp
public CIMDefinitionFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDefinitionFilter.</p>


```csharp
public CIMDefinitionFilter Clone()
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the definition expression to filter features in the dataset.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### FeatureIdentifierSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the URI of the source layer's feature identifier set (identified by GlobalID or OID)  used as the definition filter geometry.</p>


```csharp
public string FeatureIdentifierSetURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMDefinitionFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMDefinitionFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometrySource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the definition filter geometry source.</p>


```csharp
public DefinitionFilterGeometrySource GeometrySource { get; set; }
```
### GeometryURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the URI to the geometry to filter features in the dataset.</p>


```csharp
public string GeometryURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the name of the Definition Filter item.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SearchOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the search order option.</p>


```csharp
public esriSearchOrder SearchOrder { get; set; }
```
### SourceLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the source layer URI for feature-linked definition filter geometry.</p>


```csharp
public string SourceLayerURI { get; set; }
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Gets or sets the spatial reference of the definition filter geometry.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDefinitionFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDefinitionFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


