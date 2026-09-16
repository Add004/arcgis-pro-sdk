# ICatalogWindow

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Use this interface to change the catalog dock pane content and
secondary content for the portal content type</p>


## Object Signature

```csharp
public interface ICatalogWindow
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">The catalog content can only be manipulated if the active window
in the application is the catalog dock pane. See <xref href="ArcGIS.Desktop.Core.ICatalogWindow.IsActiveWindow" data-throw-if-not-resolved="false"></xref>.
Otherwise requests to change the displayed content type or secondary portal
content type will be ignored. The <xref href="ArcGIS.Desktop.Core.CatalogContentType.Portal" data-throw-if-not-resolved="false"></xref> content
type must be the current content type to change the
<xref href="ArcGIS.Desktop.Core.CatalogSecondaryPortalContentType" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### GetCurrentContentType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Gets the current catalog content type being shown in the
catalog dock pane</p>


```csharp
CatalogContentType GetCurrentContentType()
```
### GetCurrentSecondaryPortalContentType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Gets the current catalog secondary portal content type being
shown in the catalog dock pane</p>


```csharp
CatalogSecondaryPortalContentType GetCurrentSecondaryPortalContentType()
```
### IsActiveWindow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Gets whether the catalog dock pane is the active window or not</p>


```csharp
bool IsActiveWindow { get; }
```
### SetContentTypeAsync(CatalogContentType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Sets the catalog content type in the catalog dock pane. This method
must be called on the <b>UI</b> thread.</p>


```csharp
void SetContentTypeAsync(CatalogContentType catalogContentType)
```
### SetSecondaryPortalContentTypeAsync(CatalogSecondaryPortalContentType)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ICatalogWindow.yml" sourcestartlinenumber="1">Sets the catalog secondary portal content type to be shown in the
catalog dock pane. This method must be called on the <b>UI</b> thread.</p>


```csharp
void SetSecondaryPortalContentTypeAsync(CatalogSecondaryPortalContentType secondaryPortalContentType)
```


