# CIMPopupLayout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Represents a grid layout for pop-up media infos.</p>


## Object Signature

```csharp
public class CIMPopupLayout : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPopupLayout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Represents a grid layout for pop-up media infos.</p>


```csharp
public CIMPopupLayout()
```
### BorderColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Gets or sets the border color.</p>


```csharp
public CIMColor BorderColor { get; set; }
```
### BorderWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Gets or sets the border width in points.</p>


```csharp
public double BorderWidth { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPopupLayout.</p>


```csharp
public CIMPopupLayout Clone()
```
### ColumnWidths

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Gets or sets the array of column width values in percentage of the table width (0-100).</p>


```csharp
public double[] ColumnWidths { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Reconstructs the CIMPopupLayout with a specified state from a JSON encoding.</p>


```csharp
public static CIMPopupLayout FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPopupLayout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPopupLayout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


