# CustomizationFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomizationFilter.yml" sourcestartlinenumber="1">Represents a filter that is consulted before commands are executed. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class CustomizationFilter
```

## Remarks

<p>
    CustomizationFilters give developers the opportunity to limit functionality. Before any DAML defined command is executed, the
    registered CustomizationFilters are consulted; if any filter returns <code>true</code>, the sequence is stopped and the command
    is not executed.
    </p>
<p>
    Use <xref href="ArcGIS.Desktop.Framework.FrameworkApplication.RegisterCustomizationFilter(ArcGIS.Desktop.Framework.Contracts.CustomizationFilter)" data-throw-if-not-resolved="false"></xref> to register a custom CustomizationFilter with the application.
    </p>


## Members

### CustomizationFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomizationFilter.yml" sourcestartlinenumber="1">Represents a filter that is consulted before commands are executed. This is an abstract class.</p>


```csharp
protected CustomizationFilter()
```
### OnCanExecuteCommand(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.CustomizationFilter.yml" sourcestartlinenumber="1">Gives a customizaiton filter the ability to disable commands.</p>


```csharp
protected virtual bool OnCanExecuteCommand(string cmdID, string moduleID)
```
### OnExecuteCommand(string)

- Kind: method


```csharp
protected virtual bool OnExecuteCommand(string ID)
```


