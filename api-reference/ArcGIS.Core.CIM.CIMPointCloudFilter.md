# CIMPointCloudFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFilter.yml" sourcestartlinenumber="1">Represents a point cloud filter.</p>


## Object Signature

```csharp
public abstract class CIMPointCloudFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFilter.yml" sourcestartlinenumber="1">Represents a point cloud filter.</p>


```csharp
protected CIMPointCloudFilter()
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFilter.yml" sourcestartlinenumber="1">Gets or sets the field used for the filter.</p>


```csharp
public string Field { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


