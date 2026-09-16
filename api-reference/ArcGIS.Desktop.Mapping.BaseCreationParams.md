# BaseCreationParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.BaseCreationParams.yml" sourcestartlinenumber="1">A base class to create map members with pre-defined properties.
Use derived classes such as <xref href="ArcGIS.Desktop.Mapping.LayerCreationParams" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Desktop.Mapping.FeatureLayerCreationParams" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.Mapping.StandaloneTableCreationParams" data-throw-if-not-resolved="false"></xref> for creation of layers and standalone tables.
Use derived classes such as <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams" data-throw-if-not-resolved="false"></xref> for bulk creation of layers.</p>


## Object Signature

```csharp
public class BaseCreationParams
```


## Members

### BaseCreationParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.BaseCreationParams.yml" sourcestartlinenumber="1">Default constructor.</p>


```csharp
protected BaseCreationParams()
```
### MapMemberIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BaseCreationParams.yml" sourcestartlinenumber="1">Gets and sets the index of the MapMember in the map or group layer.
<xref href="ArcGIS.Desktop.Mapping.BaseCreationParams.MapMemberPosition" data-throw-if-not-resolved="false"></xref> must be set to <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.Index" data-throw-if-not-resolved="false"></xref> for this value to honored.
If <xref href="ArcGIS.Desktop.Mapping.BaseCreationParams.MapMemberPosition" data-throw-if-not-resolved="false"></xref> is set to <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.Index" data-throw-if-not-resolved="false"></xref> and this value is <b>NOT</b>
set, then the behavior will revert to auto arrange.</p>


```csharp
public int MapMemberIndex { get; set; }
```
### MapMemberPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.BaseCreationParams.yml" sourcestartlinenumber="1">Gets and sets the mapMember position.<br>
Specifies whether the mapMember should be auto positioned or be on the top or at the bottom.
Default value is <xref href="ArcGIS.Desktop.Mapping.MapMemberPosition.AutoArrange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public MapMemberPosition MapMemberPosition { get; set; }
```
### SetAutoGroupExplicitly(bool?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.BaseCreationParams.yml" sourcestartlinenumber="1">Derived classes must call this method to explicitly set the
auto-grouping behavior for the map member being created.</p>


```csharp
protected void SetAutoGroupExplicitly(bool? autoGroup)
```


