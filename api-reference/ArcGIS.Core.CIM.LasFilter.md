# LasFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Las filter.</p>


## Object Signature

```csharp
public class LasFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### LasFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Las filter.</p>


```csharp
public LasFilter()
```
### AreaOfInterest

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the area of interest.</p>


```csharp
public Envelope AreaOfInterest { get; set; }
```
### CheckZRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the flag enabling the Z-Range filter.</p>


```csharp
public bool CheckZRange { get; set; }
```
### ClassCodes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the class codes.</p>


```csharp
public int[] ClassCodes { get; set; }
```
### ClassFlags

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the class flags.</p>


```csharp
public int ClassFlags { get; set; }
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Reconstructs the LasFilter with a specified state from a JSON encoding.</p>


```csharp
public static LasFilter FromJson(string json)
```
### GetZRange()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets the Min and Max Z Range filter values, in meters.</p>


```csharp
public (double zMinInMeters, double zMaxInMeters) GetZRange()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Returns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the returns.</p>


```csharp
public int[] Returns { get; set; }
```
### SetZRange(double, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Sets the Min and Max Z Range filter values, in meters.</p>


```csharp
public void SetZRange(double zMinInMeters, double zMaxInMeters)
```
### SurfaceConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the surface constraints.</p>


```csharp
public string[] SurfaceConstraints { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the LasFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### ZMaxInMeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the Z maximum filter in meters.</p>


```csharp
public double ZMaxInMeters { get; }
```
### ZMinInMeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.LasFilter.yml" sourcestartlinenumber="1">Gets and sets the Z minimum filter in meters.</p>


```csharp
public double ZMinInMeters { get; }
```


