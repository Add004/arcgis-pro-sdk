# ITablePane

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Interface to the table pane.</p>


## Object Signature

```csharp
public interface ITablePane
```


## Members

### ActiveColumn

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Gets the Field of the active column in the table.</p>


```csharp
Field ActiveColumn { get; }
```
### ActiveObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Gets the ObjectID of the active row in the table.</p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="3">The value of the row can be null, when the table does not have object ids,
the active row is the new row, or the data for the row has not been loaded.</p>


```csharp
long? ActiveObjectID { get; }
```
### BringIntoView(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Scroll the table grid to the desired row and keep the current field.</p>


```csharp
Task BringIntoView(int rowIndex)
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Gets the Layer or StandaloneTable source of the table.</p>


```csharp
MapMember MapMember { get; }
```
### SetZoomLevel(int)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Set the zoom level for the table. The allowed values are 50 to 400.</p>


```csharp
void SetZoomLevel(int zoomLevel)
```
### ZoomLevel

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ITablePane.yml" sourcestartlinenumber="1">Gets the zoom level for the table.</p>


```csharp
int ZoomLevel { get; }
```


