# CIMTerrainAttributeRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Represents a terrain attribute renderer.</p>


## Object Signature

```csharp
public abstract class CIMTerrainAttributeRenderer : CIMTinRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTerrainAttributeRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Represents a terrain attribute renderer.</p>


```csharp
protected CIMTerrainAttributeRenderer()
```
### AttributeFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Gets or sets an attribute field name.</p>


```csharp
public string AttributeFieldName { get; set; }
```
### EmbeddedDataSources

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Gets or sets embedded data sources.</p>


```csharp
public int[] EmbeddedDataSources { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainAttributeRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


