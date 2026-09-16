# LayerCreationRollbackBehavior

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="1">Details the set of rollback behaviors for the <xref href="ArcGIS.Desktop.Mapping.LayerFactory.CreateLayers(ArcGIS.Desktop.Mapping.BulkLayerCreationParams%2cArcGIS.Desktop.Mapping.ILayerContainerEdit)" data-throw-if-not-resolved="false"></xref>
method when the BulkLayerCreationParams object is created with a set of LayerCreationParams objects.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="6">CreateLayers will create the layers it is able to per the data supplied. If invalid data sources are supplied, there will
be a mismatch in the number of layers created (and returned from the function) compared to the number of data items supplied.
When a set of LayerCreationParams objects exist, the bulk layer creation process applies the appropriate individual layer
properties to the created layers, skipping the layer properties for any data sources that are in error.
However there may be situations where this logic cannot be correctly applied and so the layers are still created
but without the individual properties applied.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="15">Use the <xref href="ArcGIS.Desktop.Mapping.BulkLayerCreationParams.RollbackBehavior" data-throw-if-not-resolved="false"></xref> to control the behavior of bulk layer creation in these
scenarios.</p>


## Object Signature

```csharp
public enum LayerCreationRollbackBehavior
```


## Members

### NoRollback

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="1">No rollback of the layer creation process occurs.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="5">The CreateLayers method will create the layers it is able to per the data supplied.
Individual layer properties are applied if possible.  If not, then
the layers created do not have these properties applied.</p>


```csharp
NoRollback = 0
```
### RollbackOnCannotApplyLayerProperties

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="1">The layer creation process is rolled back if there is a mismatch in the number of
layers created compared to the number of data sources supplied AND the correct
individual layer properties cannot be applied.</p>


```csharp
RollbackOnCannotApplyLayerProperties = 2
```
### RollbackOnMissingLayers

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.LayerCreationRollbackBehavior.yml" sourcestartlinenumber="1">The layer creation process is rolled back if there is a mismatch in the number of
layers created compared to the number of data sources supplied.</p>


```csharp
RollbackOnMissingLayers = 1
```


