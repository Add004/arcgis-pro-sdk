# ElementInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Associated element properties for use when creating elements</p>


## Object Signature

```csharp
public class ElementInfo
```


## Members

### ElementInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public ElementInfo()
```
### Anchor

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Gets and sets the default element anchor placement for layout elements. Use this
property to override the default placement.</p>


```csharp
public Anchor Anchor { get; set; }
```
### CornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Gets and sets corner rounding for elements.</p>


```csharp
public double CornerRounding { get; set; }
```
### CreateElementInfo(Anchor, double?, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Create an ElementInfo with the specified settings</p>


```csharp
public static ElementInfo CreateElementInfo(Anchor anchor, double? rotation, double cornerRounding)
```
### CreateElementInfo(Anchor, double?, double, IEnumerable&lt;CIMStringMap&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Create an ElementInfo with the specified settings</p>


```csharp
public static ElementInfo CreateElementInfo(Anchor anchor, double? rotation, double cornerRounding, IEnumerable<CIMStringMap> customProperties)
```
### CreateElementInfo(IEnumerable&lt;CIMStringMap&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Create an ElementInfo with the specified custom properties</p>


```csharp
public static ElementInfo CreateElementInfo(IEnumerable<CIMStringMap> customProperties)
```
### CreateElementInfos(Anchor, double?, double, IEnumerable&lt;IEnumerable&lt;CIMStringMap&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Create a collection of ElementInfos, one per custom properties collection</p>


```csharp
public static IList<ElementInfo> CreateElementInfos(Anchor anchor, double? rotation, double cornerRounding, IEnumerable<IEnumerable<CIMStringMap>> customProperties)
```
### CreateElementInfos(IEnumerable&lt;IEnumerable&lt;CIMStringMap&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Create a collection of ElementInfos, one per custom properties collection</p>


```csharp
public static IList<ElementInfo> CreateElementInfos(IEnumerable<IEnumerable<CIMStringMap>> customProperties)
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Gets and sets any associated custom properties</p>


```csharp
public IList<CIMStringMap> CustomProperties { get; set; }
```
### Rotation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.ElementInfo.yml" sourcestartlinenumber="1">Gets and sets the default element rotation for elements. Use this
property to override the default rotation</p>


```csharp
public double? Rotation { get; set; }
```


