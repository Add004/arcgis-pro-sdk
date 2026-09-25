# CatalogDataset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.CatalogDataset.yml" sourcestartlinenumber="1">Represents a catalog dataset. A catalog dataset is the container for item
references, which are called catalog dataset items - not unlike raster
references stored in a raster catalog</p>


## Object Signature

```csharp
public sealed class CatalogDataset : FeatureClass, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.Mapping.CatalogDataset.yml" sourcestartlinenumber="1">Catalog datasets function similarly to polygon feature classes, with some
essential differences. When viewing the dataset's attribute table, each record is an
item in the catalog dataset containing a reference to its data path. The Shape field
includes the footprint geometry for each item. This means that all catalog dataset
items must have a spatial geometry — you cannot add tables or table web layers to catalog
datasets.<br>
The footprint envelopes all of the item's features, rasters, and so forth. Each footprint
feature's attributes are properties specific to the purpose, scope, and validation status
of each dataset item.You can add, update, and maintain your own fields and values in the
dataset's attribute table, and establish a join or relate with other tables, but you cannot
access or edit the attribute table of the containing footprint layer.</p>


## Members

### CreateRow(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.CatalogDataset.yml" sourcestartlinenumber="1">Creates a new catalog dataset feature in the feature class with a system assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CatalogDatasetFeature CreateRow(RowBuffer featureBuffer)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.CatalogDataset.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Mapping.CatalogDatasetDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.</p>


```csharp
public CatalogDatasetDefinition GetDefinition()
```


