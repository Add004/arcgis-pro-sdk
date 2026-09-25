# BulkMapMemberCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">A base class to bulk create map members with pre-defined properties.
Use derived classes such as <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> for bulk creation of layers.</p>


## Object Signature

```csharp
public class BulkMapMemberCreationParams : BaseCreationParams
```


## Members

### BulkMapMemberCreationParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
protected BulkMapMemberCreationParams()
```
### BulkMapMemberCreationParams(IEnumerable&lt;CIMDataConnection&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected BulkMapMemberCreationParams(IEnumerable<CIMDataConnection> dataConnections)
```
### BulkMapMemberCreationParams(IEnumerable&lt;CIMLayerDocument&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected BulkMapMemberCreationParams(IEnumerable<CIMLayerDocument> layerDocuments)
```
### BulkMapMemberCreationParams(IEnumerable&lt;Item&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
protected BulkMapMemberCreationParams(IEnumerable<Item> items)
```
### BulkMapMemberCreationParams(IEnumerable&lt;Uri&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an enumeration of uris.</p>


```csharp
protected BulkMapMemberCreationParams(IEnumerable<Uri> uris)
```
### AutoGroup

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Gets and sets whether the map members being created should be automatically grouped</p>


```csharp
public virtual bool? AutoGroup { get; set; }
```
### DataConnections

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<CIMDataConnection> DataConnections { get; protected set; }
```
### Items

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<Item> Items { get; protected set; }
```
### LayerDocuments

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the set of <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<CIMLayerDocument> LayerDocuments { get; protected set; }
```
### Uris

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BulkMapMemberCreationParams.yml" sourcestartlinenumber="1">Gets the set of <xref href="System.Uri" data-throw-if-not-resolved="false"></xref> that represents the paths or urls to a group of datasets or .lyrx or .lpkx files.</p>


```csharp
public IReadOnlyList<Uri> Uris { get; protected set; }
```


