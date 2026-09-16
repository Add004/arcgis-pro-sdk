# MDSaveAsHTMLOption

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsHTMLOption.yml" sourcestartlinenumber="1">Enumeration of options for saving an item’s ArcGIS metadata to an HTML file. The item’s metadata content can be exported to
HTML format for display or use outside the ArcGIS platform. The XSLT stylesheet used to perform this conversion is indicated
by the option selected.</p>


## Object Signature

```csharp
public enum MDSaveAsHTMLOption
```


## Members

### esriArcGISBrief

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsHTMLOption.yml" sourcestartlinenumber="1">The XSLT that is used to display metadata with the Item Description metadata style will be used to generate an HTML file
that displays only the most essential content stored in the item’s metadata.</p>


```csharp
esriArcGISBrief = 1
```
### esriArcGISFull

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsHTMLOption.yml" sourcestartlinenumber="1">The XSLT that is used to display all metadata content when one of the standard-format metadata styles will be used to
generate an HTML file that displays all ArcGIS metadata content.</p>


```csharp
esriArcGISFull = 2
```
### esriCurrentMetadataStyle

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Core.MDSaveAsHTMLOption.yml" sourcestartlinenumber="1">The XSLT that is used to display metadata for the currently selected metadata style will be used to generate an HTML file.</p>


```csharp
esriCurrentMetadataStyle = 0
```


