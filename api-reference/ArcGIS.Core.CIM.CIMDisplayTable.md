# CIMDisplayTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Represents a display table.</p>


## Object Signature

```csharp
public abstract class CIMDisplayTable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">A display table represents a virtual view of one or more tables. The display table always has a base table, but one or more tables can be joined and/or related to the base table. A join effectively adds new columns onto the base table, based on the foreign key to the joined table. A relate simply sets up an in-memory relationship class to another table to lookup related rows from a foreign key in the base table. The display table also supports a definition expression and allows the user to specify a 'display field', whose value is a label used to represent a row in the table.</p>


## Members

### CIMDisplayTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Represents a display table.</p>


```csharp
protected CIMDisplayTable()
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the active range name.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### AllowNativeQueries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the SQL in a definition query can contain native SQL syntax.</p>


```csharp
public bool AllowNativeQueries { get; set; }
```
### BindVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the bind variables.</p>


```csharp
public CIMBindVariable[] BindVariables { get; set; }
```
### DatabaseRelates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets overrides for database relationships as relationship info.
<remarks>
By default this property is null. This will contain relationship info elements for those database relationships that have overrides.
</remarks></p>


```csharp
public CIMDatabaseRelateInfo[] DatabaseRelates { get; set; }
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the definition expression that can subset the rows in the layer or table.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### DefinitionExpressionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the name of the active definition expression.</p>


```csharp
public string DefinitionExpressionName { get; set; }
```
### DefinitionFilterChoices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the definition filter choices.</p>


```csharp
public CIMDefinitionFilter[] DefinitionFilterChoices { get; set; }
```
### DisplayExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the expression information used for coming up with a string that represents a row or a feature. This property takes precedence over <xref href="ArcGIS.Core.CIM.CIMDisplayTable.DisplayField" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CIMExpressionInfo DisplayExpressionInfo { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the name of the attribute field that will be used as a label that represents each row in the layer or table. The display field must be able to be represented as a string (string or numeric).</p>


```csharp
public string DisplayField { get; set; }
```
### Editable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the layer or table can be edited.</p>


```csharp
public bool Editable { get; set; }
```
### FieldDescriptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the field descriptions. Field descriptions for fields may only be written if values are overridden from defaults.</p>


```csharp
public CIMFieldDescription[] FieldDescriptions { get; set; }
```
### FloorAwareTableProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets floor-aware properties for the layer or table used in floor filtering.</p>


```csharp
public CIMFloorAwareTableProperties FloorAwareTableProperties { get; set; }
```
### FormInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the form information for the layer or table.</p>


```csharp
public CIMFormInfo FormInfo { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the range definitions.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Relates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the relates.</p>


```csharp
public CIMRelateInfoBase[] Relates { get; set; }
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the route identifier field of a route feature class.</p>


```csharp
public string RouteIDFieldName { get; set; }
```
### SelectRelatedData

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether related data should be selected when creating a new selection.</p>


```csharp
public bool SelectRelatedData { get; set; }
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the layer or table.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### SubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the subtype value that should be used in the feature layer definition. This property is honored only when feature layer is a member of SubtypeLayer.</p>


```csharp
public int SubtypeValue { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDimensionFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the time definition fields.</p>


```csharp
public CIMTimeDimensionDefinition TimeDimensionFields { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### TimeFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets the time fields.</p>


```csharp
public CIMTimeTableDefinition TimeFields { get; set; }
```
### UseSubtypeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the SubtypeValue should be used.</p>


```csharp
public bool UseSubtypeValue { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


