# CIMPrinterPreferences

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Represents the printer preferences associated with a layout.</p>


## Object Signature

```csharp
public class CIMPrinterPreferences : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPrinterPreferences()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Represents the printer preferences associated with a layout.</p>


```csharp
public CIMPrinterPreferences()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPrinterPreferences.</p>


```csharp
public CIMPrinterPreferences Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Reconstructs the CIMPrinterPreferences with a specified state from a JSON encoding.</p>


```csharp
public static CIMPrinterPreferences FromJson(string json, JsonDeserializationSettings settings = null)
```
### PaperName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Gets or sets the paper size name.</p>


```csharp
public string PaperName { get; set; }
```
### PaperSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Gets or sets the paper source.</p>


```csharp
public int PaperSource { get; set; }
```
### PrinterName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Gets or sets the printer name.</p>


```csharp
public string PrinterName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPrinterPreferences and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPrinterPreferences.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


