# PopupContent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Represents the content to be displayed in a custom pop-up.</p>


## Object Signature

```csharp
public class PopupContent : PropertyChangedBase
```


## Members

### PopupContent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent()
```
### PopupContent(MapMember, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent(MapMember mapMember, long oid)
```
### PopupContent(MapMember, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent(MapMember mapMember, string id_string)
```
### PopupContent(MapMember, string, long)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent(MapMember mapMember, string id_string, long oid)
```
### PopupContent(string, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent(string htmlContent, string title)
```
### PopupContent(Uri, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Initialize a new instance of PopupContent.</p>


```csharp
public PopupContent(Uri htmlURI, string title)
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the category for grouping of the pop-up.</p>


```csharp
public string Category { get; set; }
```
### CoordinateString

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets the coordinate string</p>


```csharp
public string CoordinateString { get; }
```
### HasMValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets whether the content has an M value</p>


```csharp
public bool HasMValue { get; }
```
### HtmlContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets the html content to display in the pop-up.</p>


```csharp
public string HtmlContent { get; set; }
```
### HtmlURI

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the path to the html content to display in the pop-up.</p>


```csharp
public Uri HtmlURI { get; set; }
```
### IDString

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets a &quot;generic string feature id&quot; associated with the pop-up. Can be empty if the pop-up is not associated with a feature using a string.</p>


```csharp
public string IDString { get; set; }
```
### IncludeNameInCaption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the property indicating that the caption of the pop-up includes the MapMember name and Title.</p>


```csharp
public bool IncludeNameInCaption { get; set; }
```
### IsDynamicContent

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the content for the pop-up should be created the first time it is loaded in the window.</p>


```csharp
public bool IsDynamicContent { get; set; }
```
### MValueString

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets the m value as a string</p>


```csharp
public string MValueString { get; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the MapMember associated with the pop-up. Can be null if the pop-up is not tied to a specific MapMember.</p>


```csharp
public MapMember MapMember { get; set; }
```
### ObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the objectID associated with the pop-up. Can be -1 if the pop-up is not tied to a specific object id.</p>


```csharp
public long ObjectID { get; set; }
```
### OnCreateHtmlContent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Occurs the first time the content for the item is requested. This method is only called if the <xref href="ArcGIS.Desktop.Mapping.PopupContent.IsDynamicContent" data-throw-if-not-resolved="false"></xref> property is true.</p>


```csharp
protected virtual Task<string> OnCreateHtmlContent()
```
### RelatedDataCIMDefinitionXML

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets and sets the related CIM definition</p>


```csharp
public string RelatedDataCIMDefinitionXML { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the text shown to identify the content. This property will be updated automatically if the content is not set.</p>


```csharp
public string Title { get; set; }
```
### XPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the property indicating x coordinate for the feature's position in the map.</p>


```csharp
public double XPosition { get; set; }
```
### YPosition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PopupContent.yml" sourcestartlinenumber="1">Gets or sets the property indicating y coordinate for the feature's position in the map.</p>


```csharp
public double YPosition { get; set; }
```


