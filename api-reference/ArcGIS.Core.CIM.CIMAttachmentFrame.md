# CIMAttachmentFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Represents an attachment graphic frame.</p>


## Object Signature

```csharp
public class CIMAttachmentFrame : CIMFrameElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAttachmentFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Represents an attachment graphic frame.</p>


```csharp
public CIMAttachmentFrame()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAttachmentFrame.</p>


```csharp
public CIMAttachmentFrame Clone()
```
### EmptyPlaceholderText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the text to display when no attachment images are available.</p>


```csharp
public string EmptyPlaceholderText { get; set; }
```
### EmptyPlaceholderTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the empty placeholder text.</p>


```csharp
public CIMSymbolReference EmptyPlaceholderTextSymbol { get; set; }
```
### ExcludedCells

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the list of excluded grid cells. Cells that are excluded are left blank when the report is exported.</p>


```csharp
public string ExcludedCells { get; set; }
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the attachment filter type. The filter attachment type determines which attachments from the feature that are used in the exported report.</p>


```csharp
public AttachmentFilterType FilterType { get; set; }
```
### FilterValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the filter value. When using the First or Last attachment filter type, the value indicates the number of attachments to use in the grid configuration. When using the Index attachment filter type, the value indicates the index and is zero-based.</p>


```csharp
public int FilterValue { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMAttachmentFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMAttachmentFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridColumns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the number of attachment image columns.</p>


```csharp
public int GridColumns { get; set; }
```
### GridRowDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the grid layout is in row major order.</p>


```csharp
public bool GridRowDirection { get; set; }
```
### GridRows

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the number of attachment image rows. If less than 0, the number of rows is automatically calculated.</p>


```csharp
public int GridRows { get; set; }
```
### ImageFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the graphic symbology of each attachment image frame.</p>


```csharp
public CIMGraphicFrame ImageFrame { get; set; }
```
### ImageHeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the height of each attachment image.</p>


```csharp
public double ImageHeight { get; set; }
```
### ImageRotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the rotation of all attachment images. The value is in degrees counterclockwise.</p>


```csharp
public double ImageRotation { get; set; }
```
### ImageRotationExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the rotation of each attachment image using an expression. This value overrides the ImageRotation value.</p>


```csharp
public CIMExpressionInfo ImageRotationExpression { get; set; }
```
### ImageWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the width of each attachment image.</p>


```csharp
public double ImageWidth { get; set; }
```
### MaxImages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets maximum number of image attachments to display. If -1, all images attachments will be available.</p>


```csharp
public int MaxImages { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowEmptyPlaceholder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a text placeholder when no attachment images are available.</p>


```csharp
public bool ShowEmptyPlaceholder { get; set; }
```
### SortFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets field name to sort.</p>


```csharp
public string SortFieldName { get; set; }
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets sort order of image attachments.</p>


```csharp
public FieldSortInfo SortOrder { get; set; }
```
### StartOnNewPage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the first attachment image should start on a new page.</p>


```csharp
public bool StartOnNewPage { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAttachmentFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Gets or sets the where clause that queries the attachment table. The where clause is used before applying the filter type.
For example, CONTENT_TYPE = 'image/jpeg'.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


