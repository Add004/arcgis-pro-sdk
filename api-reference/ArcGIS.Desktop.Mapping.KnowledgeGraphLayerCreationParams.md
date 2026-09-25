# KnowledgeGraphLayerCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayer" data-throw-if-not-resolved="false"></xref> with pre-defined properties such as a filter set,
visibility, etc..</p>


## Object Signature

```csharp
public class KnowledgeGraphLayerCreationParams : LayerCreationParams
```


## Members

### KnowledgeGraphLayerCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphLayerCreationParams(CIMDataConnection dataConnection)
```
### KnowledgeGraphLayerCreationParams(KnowledgeGraph)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphLayerCreationParams(KnowledgeGraph knowledgeGraph)
```
### KnowledgeGraphLayerCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphLayerCreationParams(Item item)
```
### KnowledgeGraphLayerCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraphLayerCreationParams(Uri uri)
```
### IDSet

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Limits the content of the KnowledgeGraph composite layer to the
Named Object types and associated records in the IDSet.</p>


```csharp
public KnowledgeGraphLayerIDSet IDSet { get; set; }
```
### KnowledgeGraph

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.KnowledgeGraphLayerCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraph" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public KnowledgeGraph KnowledgeGraph { get; protected set; }
```


