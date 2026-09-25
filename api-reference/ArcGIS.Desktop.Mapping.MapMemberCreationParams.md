# MapMemberCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">A base class to create map members with pre-defined properties.
Use derived classes such as <xref href="ArcGIS.Desktop.Mapping.LayerCreationParams" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.FeatureLayerCreationParams" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.Mapping.StandaloneTableCreationParams" data-throw-if-not-resolved="false"></xref> for creation of layers and standalone tables.</p>


## Object Signature

```csharp
public class MapMemberCreationParams : BaseCreationParams
```


## Members

### MapMemberCreationParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
protected MapMemberCreationParams()
```
### MapMemberCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapMemberCreationParams(CIMDataConnection dataConnection)
```
### MapMemberCreationParams(CIMLayerDocument)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapMemberCreationParams(CIMLayerDocument layerDoc)
```
### MapMemberCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapMemberCreationParams(Item item)
```
### MapMemberCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected MapMemberCreationParams(Uri uri)
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.
Ignored by <xref href="ArcGIS.Desktop.Mapping.GroupLayerCreationParams" data-throw-if-not-resolved="false"></xref></p>


```csharp
public CIMDataConnection DataConnection { get; protected set; }
```
### Item

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.
Ignored by <xref href="ArcGIS.Desktop.Mapping.GroupLayerCreationParams" data-throw-if-not-resolved="false"></xref></p>


```csharp
public Item Item { get; protected set; }
```
### LayerDocument

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.
Ignored by <xref href="ArcGIS.Desktop.Mapping.GroupLayerCreationParams" data-throw-if-not-resolved="false"></xref></p>


```csharp
public CIMLayerDocument LayerDocument { get; protected set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Gets and sets the mapMember name.
If not provided, the default display name gets used e.g. the dataset name or alias. (default value = &quot;&quot;)</p>


```csharp
public string Name { get; set; }
```
### Uri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="System.Uri" data-throw-if-not-resolved="false"></xref> that represents the path or url to a dataset or .lyrx or .lpkx file.
Ignored by <xref href="ArcGIS.Desktop.Mapping.GroupLayerCreationParams" data-throw-if-not-resolved="false"></xref></p>


```csharp
public Uri Uri { get; protected set; }
```


