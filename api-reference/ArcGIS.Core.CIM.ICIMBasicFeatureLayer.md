# ICIMBasicFeatureLayer

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Provides a mechanism for accessing and setting properties of feature layers</p>


## Object Signature

```csharp
public interface ICIMBasicFeatureLayer
```


## Members

### FeatureTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets and sets a feature table.</p>


```csharp
CIMFeatureTable FeatureTable { get; set; }
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating selectability.</p>


```csharp
bool Selectable { get; set; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets and sets the selection color.</p>


```csharp
CIMColor SelectionColor { get; set; }
```
### SelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets and sets the selection symbol.</p>


```csharp
CIMSymbolReference SelectionSymbol { get; set; }
```
### UseSelectionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.ICIMBasicFeatureLayer.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether or not to use the selection symbol.</p>


```csharp
bool UseSelectionSymbol { get; set; }
```


