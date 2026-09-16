# FeatureLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a feature layer with pre-defined properties such as renderer, visibility, definition query etc..</p>


## Object Signature

```csharp
public class FeatureLayerCreationParams : LayerCreationParams
```


## Members

### FeatureLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureLayerCreationParams(CIMDataConnection dataConnection)
```
### FeatureLayerCreationParams(CIMLayerDocument)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureLayerCreationParams(CIMLayerDocument layerDoc)
```
### FeatureLayerCreationParams(FeatureClass)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureLayerCreationParams(FeatureClass featureClass)
```
### FeatureLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureLayerCreationParams(Item item)
```
### FeatureLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureLayerCreationParams(Uri uri)
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a definition query with name.</p>


```csharp
public DefinitionQuery DefinitionQuery { get; set; }
```
### FeatureClass

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClass FeatureClass { get; protected set; }
```
### RendererDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FeatureLayerCreationParams.yml" sourcestartlinenumber="1">Gets and sets a <xref href="ArcGIS.Desktop.Mapping.RendererDefinition" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RendererDefinition RendererDefinition { get; set; }
```


