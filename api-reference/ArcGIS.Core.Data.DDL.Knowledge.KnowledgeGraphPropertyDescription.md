# KnowledgeGraphPropertyDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.Knowledge.html">Knowledge</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class KnowledgeGraphPropertyDescription : FieldDescription
```


## Members

### KnowledgeGraphPropertyDescription(FieldDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(FieldDescription fieldDesc)
```
### KnowledgeGraphPropertyDescription(Field)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(Field field)
```
### KnowledgeGraphPropertyDescription(KnowledgeGraphProperty)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(KnowledgeGraphProperty property)
```
### KnowledgeGraphPropertyDescription(string, Field)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(string name, Field field)
```
### KnowledgeGraphPropertyDescription(string, FieldType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(string name, FieldType fieldType)
```
### KnowledgeGraphPropertyDescription(string, KnowledgeGraphProperty)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a <xref href="ArcGIS.Core.Data.Knowledge.KnowledgeGraphProperty" data-throw-if-not-resolved="false"></xref> description.</p>


```csharp
public KnowledgeGraphPropertyDescription(string name, KnowledgeGraphProperty property)
```
### CreateIntegerProperty(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a property description of <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> integer.</p>


```csharp
public static KnowledgeGraphPropertyDescription CreateIntegerProperty(string name)
```
### CreateStringProperty(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.Knowledge.KnowledgeGraphPropertyDescription.yml" sourcestartlinenumber="1">Creates a property description of <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> string.</p>


```csharp
public static KnowledgeGraphPropertyDescription CreateStringProperty(string name, int length)
```


