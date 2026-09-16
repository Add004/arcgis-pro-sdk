# CIMVideoPresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Represents an video media presentation page.</p>


## Object Signature

```csharp
public class CIMVideoPresentationPage : CIMPresentationPage, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVideoPresentationPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Represents an video media presentation page.</p>


```csharp
public CIMVideoPresentationPage()
```
### AutoPlay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to start playing the video automatically.</p>


```csharp
public bool AutoPlay { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVideoPresentationPage.</p>


```csharp
public CIMVideoPresentationPage Clone()
```
### EndTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the number of seconds in the video at which to end playing.</p>


```csharp
public double EndTime { get; set; }
```
### FitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the video content fit type.</p>


```csharp
public PresentationMediaContentFitType FitType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Reconstructs the CIMVideoPresentationPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMVideoPresentationPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### Loop

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to play the video in a loop.</p>


```csharp
public bool Loop { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the number of seconds in the video at which to start playing.</p>


```csharp
public double StartTime { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVideoPresentationPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VideoSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the data connection of the video.</p>


```csharp
public CIMVideoDataConnection VideoSource { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVideoPresentationPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


