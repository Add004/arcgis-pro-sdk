# ItemInfoValue

- Type: struct
- Namespace: <a class="xref" href="ESRI.html">ESRI</a>.<a class="xref" href="ESRI.ArcGIS.html">ArcGIS</a>.<a class="xref" href="ESRI.ArcGIS.ItemIndex.html">ItemIndex</a>
- Assembly: ESRI.ArcGIS.ItemIndex.dll

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Represents the underlying details associated with a <xref href="ArcGIS.Desktop.Core.Item" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
[ComVisible(true)]
public struct ItemInfoValue
```

## Remarks

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">An ItemInfoValue is always associated with an Item. Its primary purpose in the
public API is for developers of custom items.<br>The item's ItemInfoValue contains many of the item's details
to include title, description, path, type id (read from the Config.daml),
associated tags (if any), and so forth. In most cases, Pro constructs the ItemInfoValue
for you using the values for your custom item component entry in the Config.daml. It
is typically passed to its &quot;containing&quot; Item when the Item is constructed.</p>


## Members

### Deserialize(string)

- Kind: method

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Deserializes the xml string; assigning the ItemInfovalue properties.</p>


```csharp
public void Deserialize(string xml)
```
### Reset()

- Kind: method

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Clears the ItemInfoValue. Properties are set to <b>string.Empty</b>.</p>


```csharp
public void Reset()
```
### Serialize()

- Kind: method

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Outputs the current item information into an xml string.</p>


```csharp
public string Serialize()
```
### accessConstraints

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets any information on license or restrictions related to the item.</p>


```csharp
public string accessConstraints
```
### browseDialogOnly

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets whether the item will only be browsed.</p>


```csharp
public string browseDialogOnly
```
### catalogPath

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the path used to access the item.</p>


```csharp
public string catalogPath
```
### creationTime

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the date on which the item was created.</p>


```csharp
public string creationTime
```
### credits

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets any information on the source of the item and its copyright status.</p>


```csharp
public string credits
```
### culture

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the item's locale information (language and country).</p>


```csharp
public string culture
```
### description

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a detailed description for the item.</p>


```csharp
public string description
```
### guid

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a unique id for the item.</p>


```csharp
public string guid
```
### isContainer

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets whether the associated item is a container (i.e. can contain other items).</p>


```csharp
public string isContainer
```
### lastModifiedTime

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the last date on which the item was modified.</p>


```csharp
public string lastModifiedTime
```
### maxScale

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a maximum scale associated with the item.</p>


```csharp
public double maxScale
```
### minScale

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a minimum scale associated with the item.</p>


```csharp
public double minScale
```
### name

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the name of the item.</p>


```csharp
public string name
```
### physicalPath

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a physical path to the item.</p>


```csharp
public string physicalPath
```
### portalUrl

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets portal URL to which the item belongs to</p>


```csharp
public string portalUrl
```
### propertyNames

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a comma-separated list of custom property names for an item.</p>


```csharp
public string propertyNames
```
### propertyValues

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a comma-separated list of custom property values for an item.</p>


```csharp
public string propertyValues
```
### size

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the size of data.</p>


```csharp
public long size
```
### snippet

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a summary description for the item.</p>


```csharp
public string snippet
```
### spatialReference

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the spatial reference associated with the item.</p>


```csharp
public string spatialReference
```
### tags

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets any user defined tags for the item.</p>


```csharp
public string tags
```
### thumbnailPath

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a Url to a thumbnail used for the item.</p>


```csharp
public string thumbnailPath
```
### title

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets a title for the item.</p>


```csharp
public string title
```
### type

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the content type of the item.</p>


```csharp
public string type
```
### typeFilters

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets any key words that describe the item.</p>


```csharp
public string typeFilters
```
### typeID

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">An arbitrary identifier that uniquely identifies the type of the item.</p>


```csharp
public string typeID
```
### typeInfo

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">This is not used.</p>


```csharp
public string typeInfo
```
### typeKeywords

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets any key words that describe the item.</p>


```csharp
public string typeKeywords
```
### url

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the service url of the item.</p>


```csharp
public string url
```
### workspaceFactoryID

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets an associated workspace factory for the item.</p>


```csharp
public string workspaceFactoryID
```
### xMax

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the maximum upper right x coordinate of the extent of the item.</p>


```csharp
public double xMax
```
### xMin

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the minimum lower left x coordinate of the extent of the item.</p>


```csharp
public double xMin
```
### yMax

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the maximum upper right y coordinate of the extent of the item.</p>


```csharp
public double yMax
```
### yMin

- Kind: field

<p sourcefile="api/ESRI.ArcGIS.ItemIndex.ItemInfoValue.yml" sourcestartlinenumber="1">Gets and sets the minimum lower left y coordinate of the extent of the item.</p>


```csharp
public double yMin
```


