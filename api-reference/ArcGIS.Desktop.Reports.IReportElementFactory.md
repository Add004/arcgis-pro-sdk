# IReportElementFactory

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Provides a mechanism for creating report elements.</p>


## Object Signature

```csharp
public interface IReportElementFactory
```


## Members

### CreateAttachmentFrame(IElementContainer, Envelope)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates an attachment frame element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
AttachmentFrame CreateAttachmentFrame(IElementContainer elementContainer, Envelope envelope)
```
### CreateChartFrame(IElementContainer, Envelope, MapMember, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a chartFrame element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
ChartFrame CreateChartFrame(IElementContainer elementContainer, Envelope envelope, MapMember mapMember, string chartName)
```
### CreateDynamicPictureGraphicElement(IElementContainer, Envelope, CIMReportField)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a dynamic picture element defined by a field on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateDynamicPictureGraphicElement(IElementContainer elementContainer, Envelope envelope, CIMReportField reportField)
```
### CreateDynamicPictureGraphicElement(IElementContainer, Envelope, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a dynamic picture element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateDynamicPictureGraphicElement(IElementContainer elementContainer, Envelope envelope, string url)
```
### CreateFieldStatisticTextElement(IElementContainer, Envelope, ReportFieldStatistic, CIMTextSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a field statistic text element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateFieldStatisticTextElement(IElementContainer elementContainer, Envelope envelope, ReportFieldStatistic reportFieldStatistic, CIMTextSymbol textSymbol = null)
```
### CreateFieldValueTextElement(IElementContainer, Envelope, CIMReportField, CIMTextSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a field value text element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateFieldValueTextElement(IElementContainer elementContainer, Envelope envelope, CIMReportField reportField, CIMTextSymbol textSymbol = null)
```
### CreateMapFrame(IElementContainer, Envelope, Map, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a mapFrame element on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
MapFrame CreateMapFrame(IElementContainer elementContainer, Envelope envelope, Map map, string mapFrameName)
```
### CreateRectangleParagraphGraphicElement(IElementContainer, Envelope, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a graphic rectangle text element on a layout from an envelope geometry with an added parameter to set the text symbol. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateRectangleParagraphGraphicElement(IElementContainer elementContainer, Envelope envelope, string text = null)
```
### CreateRectangleParagraphGraphicElement(IElementContainer, Envelope, string, CIMTextSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.IReportElementFactory.yml" sourcestartlinenumber="1">Creates a dynamic picture element defined by a field on a report from an envelope geometry. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
GraphicElement CreateRectangleParagraphGraphicElement(IElementContainer elementContainer, Envelope envelope, string text = null, CIMTextSymbol textSymbol = null)
```


