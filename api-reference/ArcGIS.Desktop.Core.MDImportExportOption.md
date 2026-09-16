# MDImportExportOption

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">Enumeration of options for importing metadata to and exporting metadata from an item. Used to identify the XML
format of a metadata document that will be imported, or the XML format of the metadata document that will be created
on export. An appropriate transformation will take place between the ArcGIS metadata XML format and the indicated XML
format. On import, the resulting ArcGIS metadata is saved to the item.</p>
<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="6">Remarks: On import, if the selected option identifies an XML format that doesn’t match the XML format of the source
metadata document the wrong transformation will be performed. The resulting content that is formatted as ArcGIS metadata
can be missing some or all of the original content.</p>


## Object Signature

```csharp
public enum MDImportExportOption
```


## Members

### esriCurrentMetadataStyle

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The format of the metadata document that will be imported is assumed to match the XML format of metadata standard associated with the
current metadata style. Exported metadata documents will be created in the XML format of the current metadata style.</p>


```csharp
esriCurrentMetadataStyle = 1
```
### esriCustomizedStyleSheet

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">A custom XSLT will be used to convert between ArcGIS metadata and another XML format, either during the import process or the export process.</p>


```csharp
esriCustomizedStyleSheet = 7
```
### esriDublinCorePlus

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be exported has content stored in the Dublin Core+ metadata format. This option is not supported as an import format.</p>


```csharp
esriDublinCorePlus = 9
```
### esriEsriIso

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be imported has content stored in the ESRI-ISO metadata format. For example, it may have been created
using ArcGIS Desktop 8.x or 9.x. This option is not supported as an export format.</p>


```csharp
esriEsriIso = 2
```
### esriFgdcCsdgm

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be imported has content stored in the FGDC CSDGM XML format. Or, the metadata document that will be
exported will have content stored in the FGDC CSDGM XML format.</p>


```csharp
esriFgdcCsdgm = 3
```
### esriIso19115_3

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be exported has content stored in the ISO 19115-3 version 1 metadata format.</p>


```csharp
esriIso19115_3 = 8
```
### esriIso19115_3_v2

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be exported has content stored in the ISO 19115-3 Version 2 with ISO 19110 metadata format.</p>


```csharp
esriIso19115_3_v2 = 10
```
### esriIso19139

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be imported has content stored in the ISO 19139 XML format. Or, the metadata document that will be
exported will have content stored in the ISO 19139 XML format. The GML namespace used in ISO 19139 XML document is appropriate for the
2007 version of the ISO 19139 XML Schemas: <a href="http://www.opengis.net/gml" sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="3">http://www.opengis.net/gml</a>.</p>


```csharp
esriIso19139 = 5
```
### esriIso19139Gml32

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be imported has content stored in the ISO 19139 XML format. Or, the metadata document that will be
exported will have content stored in the ISO 19139 XML format. The GML namespace used in the ISO 19139 XML document is appropriate for
the 2012 version of the ISO 19139 XML Schemas, which corresponds to the ISO 19136 version of the GML standard: <a href="http://www.opengis.net/gml/3.2" sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="3">http://www.opengis.net/gml/3.2</a>.</p>


```csharp
esriIso19139Gml32 = 4
```
### esriIso19139Unknown

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">The metadata document that will be imported has content stored in the ISO 19139 XML format. Use this option if you are unsure which GML
namespace the document is associated with. The namespace in the document will be checked and the correct conversion will be performed to
transform its content to the ArcGIS metadata XML format. This option is not supported as an export format.</p>


```csharp
esriIso19139Unknown = 6
```
### esriMetadataStyleNone

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDImportExportOption.yml" sourcestartlinenumber="1">Use this option if you are unsure what XML format is used by a metadata document. The format of the document will be checked and the
correct conversion will be performed to transform its content to the ArcGIS metadata XML format. This option is not supported as an
export format.</p>


```csharp
esriMetadataStyleNone = 0
```


