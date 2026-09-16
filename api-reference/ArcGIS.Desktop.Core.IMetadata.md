# IMetadata

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Implemented by items that support metadata</p>


## Object Signature

```csharp
public interface IMetadata
```


## Members

### CanEdit()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Indicates if metadata is editable for the item.</p>


```csharp
bool CanEdit()
```
### CopyMetadataFromItem(Item)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Copy metadata from Item</p>


```csharp
void CopyMetadataFromItem(Item sourceItem)
```
### DeleteMetadataContent(MDDeleteContentOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Delete certain content from the metadata of the current item</p>


```csharp
void DeleteMetadataContent(MDDeleteContentOption deleteOption)
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Export metadata</p>


```csharp
void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption)
```
### ExportMetadata(string, MDImportExportOption, MDExportRemovalOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Export metadata</p>


```csharp
void ExportMetadata(string outputFilePath, MDImportExportOption exportType, MDExportRemovalOption removalOption, string styleSheetPath)
```
### GetXml()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Gets the item’s metadata XML document as a string.</p>


```csharp
string GetXml()
```
### ImportMetadata(string, MDImportExportOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Import metadata</p>


```csharp
void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType)
```
### ImportMetadata(string, MDImportExportOption, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Import metadata</p>


```csharp
void ImportMetadata(string catalogPathOrMDUri, MDImportExportOption importType, string styleSheetPath)
```
### SaveMetadataAsHTML(string, MDSaveAsHTMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Save the metadata of the current item as HTML</p>


```csharp
void SaveMetadataAsHTML(string outputFilePath, MDSaveAsHTMLOption outputType)
```
### SaveMetadataAsUsingCustomXSLT(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Save the metadata of the current item using customized XSLT</p>


```csharp
void SaveMetadataAsUsingCustomXSLT(string customXSLTFilePath, string outputFilePath)
```
### SaveMetadataAsXML(string, MDSaveAsXMLOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Save the metadata of the current item as XML</p>


```csharp
void SaveMetadataAsXML(string outputFilePath, MDSaveAsXMLOption outputType)
```
### SetXml(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Sets the item’s metadata to the XML document provided as a string.</p>


```csharp
void SetXml(string xml)
```
### Synchronize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Updates metadata with the current properties of the item. Metadata is created for the item if it doesn't already exist.</p>


```csharp
string Synchronize()
```
### UpgradeMetadata(MDUpgradeOption)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.IMetadata.yml" sourcestartlinenumber="1">Upgrade the metadata of the current item</p>


```csharp
void UpgradeMetadata(MDUpgradeOption upgradeOption)
```


