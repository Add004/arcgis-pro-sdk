# esriNAImpedanceTransformationType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.esriNAImpedanceTransformationType.yml" sourcestartlinenumber="1">Location-Allocation impedance transformation type</p>


## Object Signature

```csharp
public enum esriNAImpedanceTransformationType
```


## Members

### esriNAITTExponential

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNAImpedanceTransformationType.yml" sourcestartlinenumber="1">Distance between two points will be scaled according to an exponent using a transformation parameter (e.g. distance(i,j) = e^(parameter*distance(i,j))</p>


```csharp
esriNAITTExponential = 2
```
### esriNAITTLinear

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNAImpedanceTransformationType.yml" sourcestartlinenumber="1">Distance between two points will be scaled linearly using a transformation parameter. (e.g. distance(i,j) = parameter*distance(i,j)</p>


```csharp
esriNAITTLinear = 0
```
### esriNAITTPower

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.esriNAImpedanceTransformationType.yml" sourcestartlinenumber="1">Distance between two points will be scaled according to a power using a transformation parameter (e.g. distance(i,j) = distance(i,j)^parameter</p>


```csharp
esriNAITTPower = 1
```


