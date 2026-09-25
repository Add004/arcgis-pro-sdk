# CIMStandaloneTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Represents a standalone table.</p>


## Object Signature

```csharp
public class CIMStandaloneTable : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandaloneTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Represents a standalone table.</p>


```csharp
public CIMStandaloneTable()
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the active range name.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### AllowNativeQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the SQL in a definition query can contain native SQL syntax.</p>


```csharp
public bool AllowNativeQueries { get; set; }
```
### AutoGenerateRowTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically generate row templates from the renderer.</p>


```csharp
public bool AutoGenerateRowTemplates { get; set; }
```
### BindVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the bind variables.</p>


```csharp
public CIMBindVariable[] BindVariables { get; set; }
```
### Charts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the table's charts.</p>


```csharp
public CIMChart[] Charts { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandaloneTable.</p>


```csharp
public CIMStandaloneTable Clone()
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the standalone table. Custom properties are limited to key / value pairs of strings and developers are fully responsible for stored content.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the data connection for the table.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DatabaseRelates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets overrides for database relationships as relationship info.
<remarks>
By default this property is null. This will contain relationship info elements for those database relationships that have overrides.
</remarks></p>


```csharp
public CIMDatabaseRelateInfo[] DatabaseRelates { get; set; }
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the definition expression that can subset the rows in the layer or table.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### DefinitionExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the name of the active definition expression.</p>


```csharp
public string DefinitionExpressionName { get; set; }
```
### DefinitionFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the definition filter choices.</p>


```csharp
public CIMDefinitionFilter[] DefinitionFilterChoices { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the expression information used for coming up with a string that represents a row or a feature. This property takes precedence over <xref href="ArcGIS.Core.CIM.CIMStandaloneTable.DisplayField" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the name of the attribute field that will be used as a label that represents each row in the layer or table. The display field must be able to be represented as a string (string or numeric).</p>


```csharp
public string DisplayField { get; set; }
```
### Editable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the layer or table can be edited.</p>


```csharp
public bool Editable { get; set; }
```
### FieldDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the field descriptions. Field descriptions for fields may only be written if values are overridden from defaults.</p>


```csharp
public CIMFieldDescription[] FieldDescriptions { get; set; }
```
### FloorAwareTableProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets floor-aware properties for the layer or table used in floor filtering.</p>


```csharp
public CIMFloorAwareTableProperties FloorAwareTableProperties { get; set; }
```
### FormInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the form information for the layer or table.</p>


```csharp
public CIMFormInfo FormInfo { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Reconstructs the CIMStandaloneTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandaloneTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### PageDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the page definition which allows for using current map series page to filter rows.</p>


```csharp
public CIMPageDefinition PageDefinition { get; set; }
```
### PopupInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the pop-up info.</p>


```csharp
public CIMPopupInfo PopupInfo { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the range definitions.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Relates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the relates.</p>


```csharp
public CIMRelateInfoBase[] Relates { get; set; }
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the route identifier field of a route feature class.</p>


```csharp
public string RouteIDFieldName { get; set; }
```
### RowTemplates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the row templates.</p>


```csharp
public CIMEditingTemplate[] RowTemplates { get; set; }
```
### Searchable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this table should be included in the search. This property is honored only by tables that support search.</p>


```csharp
public bool Searchable { get; set; }
```
### SelectRelatedData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether related data should be selected when creating a new selection.</p>


```csharp
public bool SelectRelatedData { get; set; }
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the layer or table.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### ServiceTableID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets identifier that will be used to identify the layer in server.</p>


```csharp
public int ServiceTableID { get; set; }
```
### ShowPopups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show pop-ups.</p>


```csharp
public bool ShowPopups { get; set; }
```
### SubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the subtype value that should be used in the feature layer definition. This property is honored only when feature layer is a member of SubtypeLayer.</p>


```csharp
public int SubtypeValue { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDimensionFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the time definition fields.</p>


```csharp
public CIMTimeDimensionDefinition TimeDimensionFields { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### TimeFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the time fields.</p>


```csharp
public CIMTimeTableDefinition TimeFields { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandaloneTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the SubtypeValue should be used.</p>


```csharp
public bool UseSubtypeValue { get; set; }
```
### UseVisibilityTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the visibility time extent. When true the map time must overlap the visibility time extent for the table to be visible.</p>


```csharp
public bool UseVisibilityTimeExtent { get; set; }
```
### VisibilityTimeExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets the visibility time extent.</p>


```csharp
public TimeExtent VisibilityTimeExtent { get; set; }
```
### WebMapTableID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Gets or sets an identifier that will be used to identify the standalone table in a web map. This value is present if the standalone table originated in a web map and facilitates matching the standalone table back to its origin when updating the web map.</p>


```csharp
public string WebMapTableID { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandaloneTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


