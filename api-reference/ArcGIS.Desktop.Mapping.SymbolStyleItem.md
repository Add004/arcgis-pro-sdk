# SymbolStyleItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Represents a symbol saved in a style.</p>


## Object Signature

```csharp
public class SymbolStyleItem : StyleItem
```


## Members

### SymbolStyleItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Creates a new instance of <xref href="ArcGIS.Desktop.Mapping.SymbolStyleItem" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public SymbolStyleItem()
```
### SymbolStyleItem(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Creates a new instance of <xref href="ArcGIS.Desktop.Mapping.SymbolStyleItem" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public SymbolStyleItem(string stylePath = "")
```
### FitSizeToSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Gets and sets whether the symbol preview image will fill the patch size or not.</p>


```csharp
public bool FitSizeToSymbol { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.CIM.CIMSymbol" data-throw-if-not-resolved="false"></xref> of the symbol style item.</p>


```csharp
public CIMSymbol Symbol { get; set; }
```
### SymbolPatchType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolStyleItem.yml" sourcestartlinenumber="1">Gets and sets the shape of the symbol patch to generate for the
preview symbol</p>


```csharp
public SymbolPatchType SymbolPatchType { get; set; }
```


