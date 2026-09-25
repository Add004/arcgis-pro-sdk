# ReportStylingManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Reports.html">Reports</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportStylingManager.yml" sourcestartlinenumber="1">Manages the report styling.</p>


## Object Signature

```csharp
public static class ReportStylingManager
```


## Members

### GetStylings()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportStylingManager.yml" sourcestartlinenumber="1">Gets the list of report stylings.  This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public static IReadOnlyList<string> GetStylings()
```
### GetStylingsAsync()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Reports.ReportStylingManager.yml" sourcestartlinenumber="1">Gets the report templates. They are loaded if needed.</p>


```csharp
public static Task<IReadOnlyList<string>> GetStylingsAsync()
```


