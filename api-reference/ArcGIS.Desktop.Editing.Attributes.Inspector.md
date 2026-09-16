# Inspector

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Provides access to the attribute values on features and rows.</p>


## Object Signature

```csharp
public sealed class Inspector : PropertyChangedBase, IEnumerable<Attribute>, IEnumerable
```

## Remarks

<p>This class is primarily used to get or set the attribute values on features or rows. Additionally it provides some meta information.<br>
    To get or set attribute values, first load a feature or row into the class then use the class properties or attribute index/name.</p>
<p>
    You can also use the Inspector class to obtain schema information about a mapMember.  Use the <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.LoadSchema(ArcGIS.Desktop.Mapping.MapMember)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector.LoadSchemaAsync(ArcGIS.Desktop.Mapping.MapMember)" data-throw-if-not-resolved="false"></xref>
    methods to obtain schema information. 
    </p>


## Members

### Inspector()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Create a new instance of the inspector class.</p>


```csharp
public Inspector()
```
### AddAttributeAsync(MapMember, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Add an <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> to the feature inspector by mapmember and field name or field alias.</p>


```csharp
public Task<Attribute> AddAttributeAsync(MapMember member, string fieldNameOrAlias, bool isAlias = false)
```
### AddAttributeAsync(string, MapMember, string, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Add an <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> to the feature inspector by mapmember, field name and/or field alias.</p>


```csharp
public Task<Attribute> AddAttributeAsync(string fieldAlias, MapMember member, string fieldNameOrAlias, bool isAlias = false)
```
### AddAttributeAsync(string, MapMember, string, bool, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Add an <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> to the feature inspector by mapmember, field name and/or field alias.</p>


```csharp
public Task<Attribute> AddAttributeAsync(string fieldAlias, MapMember member, string fieldNameOrAlias, bool isAlias, string tooltip)
```
### AllowEditing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets or sets a flag to prevent users from modifying it's fields value.</p>


```csharp
public bool AllowEditing { get; set; }
```
### Apply()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Apply the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> changes. Writing them back to the database in an Edit Operation.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool Apply()
```
### ApplyAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Apply the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> changes. Writing them back to the database in an Edit Operation.</p>


```csharp
public Task<bool> ApplyAsync()
```
### Cancel()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Cancel the Attribute changes, reverting back to the database's state.</p>


```csharp
public void Cancel()
```
### ChangeSubtype(int, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Change the <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=subtype" data-throw-if-not-resolved="false"></xref> of the features.</p>


```csharp
public bool ChangeSubtype(int proposedCode, bool propogate = false)
```
### Clear()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Clears or empties the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Clear()
```
### ClearAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Clears or empties the inspector.</p>


```csharp
public Task ClearAsync()
```
### CreateEmbeddableControl()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Creates the embeddable user control associated with this instance of the inspector.</p>


```csharp
public Tuple<EmbeddableControl, UserControl> CreateEmbeddableControl()
```
### GeometryAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the geometry (shape) attribute.</p>


```csharp
public Attribute GeometryAttribute { get; }
```
### GetAnnotationProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.AnnotationProperties" data-throw-if-not-resolved="false"></xref> for annotation features in the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AnnotationProperties GetAnnotationProperties()
```
### GetDimensionProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.DimensionProperties" data-throw-if-not-resolved="false"></xref> for dimension features in the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionProperties GetDimensionProperties()
```
### GetEnumerator()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Enables enumeration through attributes on the inspector.</p>


```csharp
public IEnumerator<Attribute> GetEnumerator()
```
### HasAnnotationAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean value indicating whether this inspector has any annotation features.</p>


```csharp
public bool HasAnnotationAttributes { get; }
```
### HasAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean value indicating whether this inspector has any attributes.</p>


```csharp
public bool HasAttributes { get; }
```
### HasDimensionAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a boolean value indicating whther this inspector has any dimension features.</p>


```csharp
public bool HasDimensionAttributes { get; }
```
### HasGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean value indicating whether this inspector has any geometry. It will return false when feature inspector has two or more features or for features
belonging to Stand Alone tables.</p>


```csharp
public bool HasGeometry { get; }
```
### HasValidAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean indicating if all of the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attributes" data-throw-if-not-resolved="false"></xref> are valid. Returns false if any
<xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attributes" data-throw-if-not-resolved="false"></xref> are not valid.</p>


```csharp
public bool HasValidAttributes { get; }
```
### HasValidEdits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean indicating if all of the edited <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attributes" data-throw-if-not-resolved="false"></xref> are valid. Returns false if any
edited <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attributes" data-throw-if-not-resolved="false"></xref> are not valid, null if no edits or IsFeature is false.</p>


```csharp
public bool? HasValidEdits { get; }
```
### IsDirty

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean indicating whether any <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> in the list of
<xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=Attributes" data-throw-if-not-resolved="false"></xref> is modified.</p>


```csharp
public bool IsDirty { get; }
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets a Boolean indicating if the feature/row is editable.</p>


```csharp
public bool IsEditable { get; }
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Returns the current value of <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref>.
Takes in the index of <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> as the parameter.</p>


```csharp
public object this[int index] { get; set; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets and sets the current value of the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> specified by <code class="paramref">fieldName</code>.</p>


```csharp
public object this[string fieldName] { get; set; }
```
### Load(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load a single row into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(Row row)
```
### Load(Table, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load multiple table rows into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(Table table, IEnumerable<long> oids)
```
### Load(Table, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load multiple table rows into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(Table table, long oid)
```
### Load(MapMember, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load multiple rows or features into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(MapMember member, IEnumerable<long> oidSet)
```
### Load(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load a single row or feature into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void Load(MapMember member, long oid)
```
### LoadAsync(MapMember, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load multiple rows or features into the inspector.</p>


```csharp
public Task LoadAsync(MapMember member, IEnumerable<long> oidSet)
```
### LoadAsync(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load a single row or feature into the inspector.</p>


```csharp
public Task LoadAsync(MapMember member, long oid)
```
### LoadSchema(Table)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load the schema of a table into the inspector.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void LoadSchema(Table table)
```
### LoadSchema(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load the schema of a mapMember into the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void LoadSchema(MapMember member)
```
### LoadSchemaAsync(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Load the schema of a mapMember into the inspector.</p>


```csharp
public Task LoadSchemaAsync(MapMember member)
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.MapMember?text=mapMember" data-throw-if-not-resolved="false"></xref> of the features.</p>


```csharp
public MapMember MapMember { get; }
```
### OIDSet

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the OID's of features loaded into an inspector.</p>


```csharp
public ReadOnlyObservableCollection<long> OIDSet { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the ObjectID for the feature loaded into an inspector.</p>


```csharp
public long ObjectID { get; }
```
### ObjectIDAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> for the ObjectID field.</p>


```csharp
public Attribute ObjectIDAttribute { get; }
```
### SetAnnotationProperties(AnnotationProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Sets annotation properties on annotation features within the inspector. This method must be called on the MCT. Uses QueuedTask.Run.</p>


```csharp
public void SetAnnotationProperties(AnnotationProperties annotationProperties)
```
### SetDimensionProperties(DimensionProperties)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Sets dimension properties on dimension features in the inspector. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDimensionProperties(DimensionProperties properties)
```
### Shape

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets or sets the geometry (shape) of objects within the inspector.</p>


```csharp
public Geometry Shape { get; set; }
```
### SubtypeAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Attributes.Subtype?text=Subtype" data-throw-if-not-resolved="false"></xref><xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=Attribute" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Attribute SubtypeAttribute { get; }
```
### TryGetValue(string, out object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Gets the current value of the <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute?text=attribute" data-throw-if-not-resolved="false"></xref> specified by <code class="paramref">fieldName</code>.</p>


```csharp
public bool TryGetValue(string fieldName, out object value)
```
### TrySetValue(string, object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Sets the value of the attribute specified by the <code class="paramref">fieldName</code>.</p>


```csharp
public bool TrySetValue(string fieldName, object value)
```
### TrySetValues(Dictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Inspector.yml" sourcestartlinenumber="1">Sets the value of the attributes specified by the dictionary of (fieldName, value) pairs.</p>


```csharp
public bool TrySetValues(Dictionary<string, object> values)
```


