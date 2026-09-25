# TextProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Represents a collection of text properties associated with a <xref href="ArcGIS.Desktop.Layouts.TextElement?text=TextElement" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class TextProperties
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Each <xref href="ArcGIS.Desktop.Layouts.TextElement?text=TextElement" data-throw-if-not-resolved="false"></xref> on a page layout has an associated set of text properties.<br>
This intermediate object allows you to change multiple text properties before pushing the changes back to the
<xref href="ArcGIS.Desktop.Layouts.TextElement?text=TextElement" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### TextProperties(string, string, double, string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Initialize a new instance of TextProperties.</p>


```csharp
public TextProperties(string text, string font, double fontSize, string fontStyle)
```
### Font

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Gets and sets the font name of the text element.  When setting, use the string values the way they appear in the Text Symbol Font list located in the text element format tab.</p>


```csharp
public string Font { get; set; }
```
### FontSize

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Gets and sets the font size of the text element.</p>


```csharp
public double FontSize { get; set; }
```
### FontStyle

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Gets and sets the string for the font style.</p>


```csharp
public string FontStyle { get; set; }
```
### Text

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.TextProperties.yml" sourcestartlinenumber="1">Gets and sets the string associated with the text element.</p>


```csharp
public string Text { get; set; }
```


