# CIMTabGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Defines a tab for a MapGrid.</p>


## Object Signature

```csharp
public abstract class CIMTabGridLine : CIMGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTabGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Defines a tab for a MapGrid.</p>


```csharp
protected CIMTabGridLine()
```
### AlternatingSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Gets or sets the alternating symbol.</p>


```csharp
public CIMSymbolReference AlternatingSymbol { get; set; }
```
### AlternatingSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether symbols for the tab are alternating.</p>


```csharp
public bool AlternatingSymbols { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Gets or sets the height of the tab. The height in defined in page units.</p>


```csharp
public double Height { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTabGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


