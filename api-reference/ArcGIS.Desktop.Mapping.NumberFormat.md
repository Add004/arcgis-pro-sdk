# NumberFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.NumberFormat.yml" sourcestartlinenumber="1">Supports formatting of values according to the input <xref href="ArcGIS.Core.CIM.CIMNumberFormat" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class NumberFormat
```


## Members

### RoundUp(CIMNumberFormat, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NumberFormat.yml" sourcestartlinenumber="1">Rounds up the input value based on the specified <xref href="ArcGIS.Core.CIM.CIMNumberFormat" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static double RoundUp(CIMNumberFormat numberFormat, double value)
```
### ValueToString(CIMNumberFormat, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.NumberFormat.yml" sourcestartlinenumber="1">Returns a formatted value based on the input <xref href="ArcGIS.Core.CIM.CIMNumberFormat" data-throw-if-not-resolved="false"></xref> and value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static string ValueToString(CIMNumberFormat numberFormat, double value)
```


