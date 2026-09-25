# TransformationsControlProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Configures the properties to be used to initialize the TransformationsControl</p>


## Object Signature

```csharp
public class TransformationsControlProperties
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">To refresh the TransformationsControl, provide an updated
TransformationsControlProperties</p>


## Members

### TransformationsControlProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Construct a TransformationsControlProperties to configure the TransformationsControl.
Use the different properties to configure the control. They are all optional.</p>


```csharp
public TransformationsControlProperties()
```
### CanEditCoordinateSystems

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets if the source coordinate systems and the target coordinate systems can be changed
in the table. If set to true, buttons will appear next to the source and target coordinate
system names for each row. These buttons will launch a coordinate system picker when clicked on.</p>


```csharp
public bool CanEditCoordinateSystems { get; set; }
```
### CanEditTransformationCollection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets if items can be added to the table (through the Add button) or removed from
the table (through the Delete button for each row) in the TransformationsControl.</p>


```csharp
public bool CanEditTransformationCollection { get; set; }
```
### NoTransformationsMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the custom message to diplay when the transformation table within
the TransformationsControl is empty.</p>


```csharp
public string NoTransformationsMessage { get; set; }
```
### ShowColumnNames

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets if column names should be displayed or not.</p>


```csharp
public bool ShowColumnNames { get; set; }
```
### ShowNoTransformationsMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets if a message (customizable with the <xref href="ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.NoTransformationsMessage" data-throw-if-not-resolved="false"></xref> property) is
displayed or not when the transformation table within the TransformationsControl is empty.</p>


```csharp
public bool ShowNoTransformationsMessage { get; set; }
```
### ShowWarningForEmptyTransformationSelection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets if a warning message is displayed if there is no initial selection for a transformation element.</p>


```csharp
public bool ShowWarningForEmptyTransformationSelection { get; set; }
```
### SourceCoordinateSystemColumnName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the column name for the source coordinate system column.</p>


```csharp
public string SourceCoordinateSystemColumnName { get; set; }
```
### SpatialFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the spatial filter. If specified, the SpatialFilter will be used to filter the available transformations for all
source and target coordinate system pairs in the table.
If not specified, all the possible transformations for a given source and target coordinate system pair
will be returned.
Additionaly, if a SpatialFilter is also defined on a given TransformationInfo object, it will override this
property (for this specific TransformationInfo object).</p>


```csharp
public Envelope SpatialFilter { get; set; }
```
### TargetCoordinateSystemColumnName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the column name for the target coordinate system column.</p>


```csharp
public string TargetCoordinateSystemColumnName { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the title for the table. This is used by screen reader technologies to announce
the name of the table. It is not used in the user interface.</p>


```csharp
public string Title { get; set; }
```
### TransformationColumnName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the column name for the transformation column.</p>


```csharp
public string TransformationColumnName { get; set; }
```
### TransformationsInfo

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationsControlProperties.yml" sourcestartlinenumber="1">Gets and sets the transformation information used to populate the table within the TransformationsControl.
Each TransformationInfo object will be used to populate one row of the table.</p>


```csharp
public IEnumerable<TransformationInfo> TransformationsInfo { get; set; }
```


