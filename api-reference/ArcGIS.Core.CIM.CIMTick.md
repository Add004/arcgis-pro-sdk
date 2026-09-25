# CIMTick

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Represents a tick of a grid.</p>


## Object Signature

```csharp
public abstract class CIMTick : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTick()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Represents a tick of a grid.</p>


```csharp
protected CIMTick()
```
### GridEndpoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Gets or sets the end point for the tick.</p>


```csharp
public CIMGridEndpoint GridEndpoint { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the tick is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Gets or sets the length of the tick in page units.</p>


```csharp
public double Length { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Gets or sets the offset of the tick in page units.</p>


```csharp
public double Offset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Gets or sets the symbol for the tick.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTick.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


