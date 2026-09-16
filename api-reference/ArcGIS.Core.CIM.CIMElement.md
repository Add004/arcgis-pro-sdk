# CIMElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">A CIM representation of an element.</p>


## Object Signature

```csharp
public abstract class CIMElement : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">A CIM representation of an element.</p>


```csharp
protected CIMElement()
```
### Anchor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets the anchor position of the element.</p>


```csharp
public Anchor Anchor { get; set; }
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the element.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this element is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### Locked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the element is locked. Each element in the contents pane has a lock icon. If the icon is shown as locked, you can not select that feature in the layout using the select tool.</p>


```csharp
public bool Locked { get; set; }
```
### LockedAspectRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the aspect ratio for an element is locked. If locked, the width and height values stretch proportionally.</p>


```csharp
public bool LockedAspectRatio { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets the name of the element.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets the rotation of the element.</p>


```csharp
public double Rotation { get; set; }
```
### RotationCenter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets the location of the anchor in page units.This is also the location the feature is rotated around.</p>


```csharp
public MapPoint RotationCenter { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the element is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


