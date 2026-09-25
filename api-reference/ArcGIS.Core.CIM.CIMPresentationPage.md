# CIMPresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Represents a presentation page.</p>


## Object Signature

```csharp
public class CIMPresentationPage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Represents a presentation page.</p>


```csharp
public CIMPresentationPage()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationPage.</p>


```csharp
public CIMPresentationPage Clone()
```
### ColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode.</p>


```csharp
[Obsolete("ColorVisionDeficiencyMode is deprecated at 3.5. Use CIMPresentation.ColorVisionDeficiencyMode instead.")]
public ColorVisionDeficiencyType ColorVisionDeficiencyMode { get; set; }
```
### ElementStorageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the URI of the storage for the graphic elements that will be overlaid on this presentation page.</p>


```csharp
public string ElementStorageURI { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the spatial extent to zoom to for the graphic elements that will be overlaid on this presentation page.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### HoldTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the hold time in seconds.</p>


```csharp
public double HoldTime { get; set; }
```
### IsAutomaticAdvancement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to automatically advance to the next page after the specified hold time.</p>


```csharp
public bool IsAutomaticAdvancement { get; set; }
```
### Locked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this page is locked.</p>


```csharp
public bool Locked { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the page margin.</p>


```csharp
public CIMMargin Margin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowBackgroundBorder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the border around the background content.</p>


```csharp
public bool ShowBackgroundBorder { get; set; }
```
### SpeakerNotes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the speaker notes for this page.</p>


```csharp
public string SpeakerNotes { get; set; }
```
### ThumbnailURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the thumbnail image.</p>


```csharp
public string ThumbnailURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Transition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the transition used to display the page.</p>


```csharp
public CIMPresentationTransition Transition { get; set; }
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this page is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


