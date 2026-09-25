# Token

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.Token.yml" sourcestartlinenumber="1">An object that describes the result of an enqueued operation.</p>


## Object Signature

```csharp
public abstract class Token
```

## Remarks

<p>There are several places where the output from one DDL operation serves as input to another operation. </p>
<p> For example, creating a feature dataset, and then creating a feature class within that feature dataset.</p>
<p>  Since operations are enqueued and processed all at once, token holds the description of the new schema object that doesn't exist yet. </p>





