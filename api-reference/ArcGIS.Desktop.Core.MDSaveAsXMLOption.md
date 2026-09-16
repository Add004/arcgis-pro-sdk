# MDSaveAsXMLOption

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsXMLOption.yml" sourcestartlinenumber="1">Enumeration of options for saving an item’s metadata to an ArcGIS metadata format XML file. The item’s ArcGIS metadata
content can be saved to an XML document where the content continues to be stored in the ArcGIS metadata XML format. The
amount of content that is filtered out of the item’s metadata depends on the option selected.</p>


## Object Signature

```csharp
public enum MDSaveAsXMLOption
```


## Members

### esriExactCopy

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsXMLOption.yml" sourcestartlinenumber="1">Save a copy of the item’s metadata to an ArcGIS metadata format XML file. The content is not filtered.</p>


```csharp
esriExactCopy = 0
```
### esriMetadataTemplate

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsXMLOption.yml" sourcestartlinenumber="1">Save a copy of the authored metadata content in the item’s metadata to an ArcGIS metadata format XML file. The item’s
synchronized properties, thumbnail, and geoprocessing history are not included. The resulting file can be used as a
metadata template.</p>


```csharp
esriMetadataTemplate = 3
```
### esriRemoveAllSensitive

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsXMLOption.yml" sourcestartlinenumber="1">Save a copy of the item’s metadata to an ArcGIS format XML file. The content is filtered to withhold local file
paths, database connection information, URLs that do not begin with http or https, and so on, if it is present.</p>


```csharp
esriRemoveAllSensitive = 2
```
### esriRemoveMachineNames

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsXMLOption.yml" sourcestartlinenumber="1">Save a copy of the item’s metadata to an ArcGIS format XML file. The content is filtered to remove machine names from
UNC paths, if they are present.</p>


```csharp
esriRemoveMachineNames = 1
```


