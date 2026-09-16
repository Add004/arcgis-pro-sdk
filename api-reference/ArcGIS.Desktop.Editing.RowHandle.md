# RowHandle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">A RowHandle represents a common structure for the many ways to reference a row.</p>


## Object Signature

```csharp
public sealed class RowHandle
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Note that the RowHandle can represent an actual Row, or one that will be created in the future (<xref href="ArcGIS.Desktop.Editing.RowToken" data-throw-if-not-resolved="false"></xref>).</p>


## Members

### RowHandle(Row)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a Row.</p>


```csharp
public RowHandle(Row row)
```
### RowHandle(Table, Guid)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a Table and global ID.</p>


```csharp
public RowHandle(Table table, Guid globalID)
```
### RowHandle(Table, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a Table and object ID.</p>


```csharp
public RowHandle(Table table, long objectID)
```
### RowHandle(Element, UtilityNetwork)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a UtilityNetwork and a utility network Element.</p>


```csharp
public RowHandle(Element element, UtilityNetwork utilityNetwork)
```
### RowHandle(RowToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a <xref href="ArcGIS.Desktop.Editing.RowToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RowHandle(RowToken token)
```
### RowHandle(MapMember, Guid)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a MapMember and global ID.</p>


```csharp
public RowHandle(MapMember mapMember, Guid globalID)
```
### RowHandle(MapMember, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Creates a new instance of the RowHandle class, created from a MapMember and object ID.</p>


```csharp
public RowHandle(MapMember mapMember, long objectID)
```
### Element

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets a utility network Element object that represents the row.</p>


```csharp
public Element Element { get; }
```
### GlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Returns the global ID of the row, if it exists.</p>


```csharp
public Guid? GlobalID { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets the MapMember (layer or standalone table) that contains this row.</p>


```csharp
public MapMember MapMember { get; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets the object ID of the row, if it exists.</p>


```csharp
public long? ObjectID { get; }
```
### Row

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets the Row, if it exists.</p>


```csharp
public Row Row { get; }
```
### Table

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets the Table, if it exists.</p>


```csharp
public Table Table { get; }
```
### Token

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets a <xref href="ArcGIS.Desktop.Editing.RowToken" data-throw-if-not-resolved="false"></xref> that references the row.</p>


```csharp
public RowToken Token { get; }
```
### UtilityNetwork

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RowHandle.yml" sourcestartlinenumber="1">Gets the UtilityNetwork of the row.</p>


```csharp
public UtilityNetwork UtilityNetwork { get; }
```


