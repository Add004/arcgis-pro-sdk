# CIMHtmlPopupFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Represents an HTML pop-up format.</p>


## Object Signature

```csharp
public class CIMHtmlPopupFormat : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMHtmlPopupFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Represents an HTML pop-up format.</p>


```csharp
public CIMHtmlPopupFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHtmlPopupFormat.</p>


```csharp
public CIMHtmlPopupFormat Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMHtmlPopupFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMHtmlPopupFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### HtmlHideFieldNameColumn

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to hide the field name column.</p>


```csharp
public bool HtmlHideFieldNameColumn { get; set; }
```
### HtmlPresentationStyle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets the presentation style.</p>


```csharp
public HtmlPopupStyle HtmlPresentationStyle { get; set; }
```
### HtmlRedirectField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets the redirect field.</p>


```csharp
public string HtmlRedirectField { get; set; }
```
### HtmlRedirectFieldPrefix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets the redirect field prefix.</p>


```csharp
public string HtmlRedirectFieldPrefix { get; set; }
```
### HtmlRedirectFieldSuffix

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets the redirect field suffix.</p>


```csharp
public string HtmlRedirectFieldSuffix { get; set; }
```
### HtmlUseCodedDomainValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use coded domain values.</p>


```csharp
public bool HtmlUseCodedDomainValues { get; set; }
```
### HtmlXSLStyleSheet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Gets or sets the XSL style sheet.</p>


```csharp
public string HtmlXSLStyleSheet { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHtmlPopupFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHtmlPopupFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


