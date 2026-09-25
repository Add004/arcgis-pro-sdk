# SubtypeGroupLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a <xref href="ArcGIS.Desktop.Mapping.SubtypeGroupLayer" data-throw-if-not-resolved="false"></xref> with pre-defined properties such as renderer, visibility etc. for each sublayer.</p>


## Object Signature

```csharp
public class SubtypeGroupLayerCreationParams : LayerCreationParams
```


## Members

### SubtypeGroupLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubtypeGroupLayerCreationParams(CIMDataConnection dataConnection)
```
### SubtypeGroupLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubtypeGroupLayerCreationParams(Item item)
```
### SubtypeGroupLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SubtypeGroupLayerCreationParams(Uri uri)
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a definition query with name.</p>


```csharp
public DefinitionQuery DefinitionQuery { get; set; }
```
### SubtypeLayers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SubtypeGroupLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a list of <xref href="ArcGIS.Desktop.Mapping.SubtypeFeatureLayerCreationParams" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public List<SubtypeFeatureLayerCreationParams> SubtypeLayers { get; set; }
```


