# CIMTableField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Represents properties for a table field.</p>


## Object Signature

```csharp
public abstract class CIMTableField : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTableField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Represents properties for a table field.</p>


```csharp
protected CIMTableField()
```
### DisplayName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the display name for the field.</p>


```csharp
public string DisplayName { get; set; }
```
### FieldOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the zero based display order.</p>


```csharp
public int FieldOrder { get; set; }
```
### Group

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this is a grouping field.</p>


```csharp
public bool Group { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the field name and unique identifier.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SortInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the options when this field is used for sorting.</p>


```csharp
public FieldSortInfo SortInfo { get; set; }
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the zero based sort order. -1 indicates field isn't used for sorting.</p>


```csharp
public int SortOrder { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Gets or sets the width of field. A value of 0 indicates &quot;auto size&quot;.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTableField.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


