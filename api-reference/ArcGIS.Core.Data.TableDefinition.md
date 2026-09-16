# TableDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TableDefinition : Definition, IDisposable
```


## Members

### DatasetType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the dataset type.</p>


```csharp
public override DatasetType DatasetType { get; }
```
### FindField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the index position for a field by name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int FindField(string fieldName)
```
### GetAliasName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the alias name of the definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetAliasName()
```
### GetAttributeRules(AttributeRuleType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of the table's attribute rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<AttributeRuleDefinition> GetAttributeRules(AttributeRuleType attributeRuleType = AttributeRuleType.All)
```
### GetContingencies()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of the table's contingencies.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Contingency> GetContingencies()
```
### GetCreatedAtField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the creation time field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetCreatedAtField()
```
### GetCreatorField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the creator field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetCreatorField()
```
### GetDefaultSubtypeCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the integer value representing the table's default subtype code.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetDefaultSubtypeCode()
```
### GetEditedAtField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the edit time field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetEditedAtField()
```
### GetEditorField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the editor field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetEditorField()
```
### GetFields()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the fields in the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Field> GetFields()
```
### GetGlobalIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the GlobalID field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetGlobalIDField()
```
### GetIndexes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of the table's <xref href="ArcGIS.Core.Data.Index" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Index> GetIndexes()
```
### GetModelName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the model name of the definition.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetModelName()
```
### GetObjectIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the ObjectID field.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetObjectIDField()
```
### GetSubtypeField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the field used to define subtypes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSubtypeField()
```
### GetSubtypes()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> of the table's subtype codes.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<Subtype> GetSubtypes()
```
### GetValidationStatusField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets the name of the ValidationStatus field. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetValidationStatusField()
```
### HasGlobalID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this table has a field containing GlobalIDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasGlobalID()
```
### HasObjectID()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this table has a field containing ObjectIDs.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool HasObjectID()
```
### IsEditorTrackingEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether editor tracking is enabled for the associated Table dataset.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsEditorTrackingEnabled()
```
### IsTimeInUTC()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.TableDefinition.yml" sourcestartlinenumber="1">Gets a value indicating whether this table stores time in UTC or database time.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsTimeInUTC()
```


