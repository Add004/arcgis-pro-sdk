# StandaloneTableCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Represents an object to initialize and create a standalone table with pre-defined properties such as a definition query.</p>


## Object Signature

```csharp
public class StandaloneTableCreationParams : MapMemberCreationParams
```


## Members

### StandaloneTableCreationParams(CIMDataConnection)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMDataConnection" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(CIMDataConnection dataConnection)
```
### StandaloneTableCreationParams(CIMLayerDocument)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Core.CIM.CIMLayerDocument" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(CIMLayerDocument layerDoc)
```
### StandaloneTableCreationParams(AttributedRelationshipClass)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with an <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(AttributedRelationshipClass attributedRelationshipClass)
```
### StandaloneTableCreationParams(Table)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(Table table)
```
### StandaloneTableCreationParams(Item)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(Item item)
```
### StandaloneTableCreationParams(Uri)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Creates a parameter object with <xref href="System.Uri" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public StandaloneTableCreationParams(Uri uri)
```
### AttributedRelationshipClass

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AttributedRelationshipClass AttributedRelationshipClass { get; protected set; }
```
### DefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Gets and sets a definition filter with name.</p>


```csharp
public DefinitionQuery DefinitionQuery { get; set; }
```
### Table

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.StandaloneTableCreationParams.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Table Table { get; protected set; }
```


