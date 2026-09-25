# CIMDateFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Represents a standard date and time format.
<a href="https://docs.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings" sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="2">https://docs.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings</a>.</p>


## Object Signature

```csharp
public class CIMDateFormat : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Examples:
&quot;MM/dd/yyyy&quot; 06/12/2020
&quot;dddd, dd MMMM yyyy&quot; Friday, 12 June 2020
&quot;dddd, dd MMMM yyyy HH:mm:ss&quot; Friday, 12 June 2020 08:30:01
&quot;MM/dd/yyyy HH:mm&quot; 06/12/2020 08:30
&quot;MM/dd/yyyy hh:mm tt&quot; 06/12/2020 08:30 AM
&quot;MMMM dd&quot; June 12
&quot;hh:mm tt&quot; 08:30 AM
&quot;HH:mm:ss&quot; 08:30:06.</p>


## Members

### CIMDateFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Represents a standard date and time format.
<a href="https://docs.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings" sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="2">https://docs.microsoft.com/en-us/dotnet/standard/base-types/standard-date-and-time-format-strings</a>.</p>


```csharp
public CIMDateFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDateFormat.</p>


```csharp
public CIMDateFormat Clone()
```
### Format

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Gets or sets the date format string.</p>


```csharp
public string Format { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMDateFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMDateFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDateFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDateFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


