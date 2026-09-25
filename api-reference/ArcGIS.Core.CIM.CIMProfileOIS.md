# CIMProfileOIS

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Defines the properties for OIS features.</p>


## Object Signature

```csharp
public class CIMProfileOIS : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileOIS()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Defines the properties for OIS features.</p>


```csharp
public CIMProfileOIS()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileOIS.</p>


```csharp
public CIMProfileOIS Clone()
```
### DisplayOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets the zero based index to control the display order.</p>


```csharp
public int DisplayOrder { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileOIS with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileOIS FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsPrimary

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the surface is primary.
If surface is primary it can't be hidden and terrain and obstacles will be drawn based on the primary surface.</p>


```csharp
public bool IsPrimary { get; set; }
```
### OISDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets the description of OIS surface read only.</p>


```csharp
public string OISDescription { get; set; }
```
### OISLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets the label to be displayed for OIS.</p>


```csharp
public string OISLabel { get; set; }
```
### OISSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets the line Symbol used to draw the OIS Surface.</p>


```csharp
public CIMSymbolReference OISSymbol { get; set; }
```
### OISTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets the text symbol used to draw the label of OIS Surface.</p>


```csharp
public CIMSymbolReference OISTextSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOIS

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show OIS surface.</p>


```csharp
public bool ShowOIS { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileOIS and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileOIS.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


