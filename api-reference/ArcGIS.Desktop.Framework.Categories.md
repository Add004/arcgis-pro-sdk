# Categories

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Categories.yml" sourcestartlinenumber="1">Retrieves components registered in a category.</p>


## Object Signature

```csharp
public static class Categories
```

## Remarks

<p>
     Component categories are defined in DAML. The DAML fragment below shows an example category declaration.
     </p>
<p>
  <pre><code class="lang-csharp">&lt;categories&gt;
  &lt;insertCategory id="ProjectContainers"/&gt;
&lt;/categories&gt;</code></pre>

<p>
     Anyone can then register a component in the category. A component can optionally have a content sub-element where 
     they can define any XML they wish. In the example below, just a few attributes have been added but this can be any XML desired.
     </p>
<p>
  <pre><code class="lang-csharp">&lt;categories&gt;
  &lt;updateCategory refID="ProjectContainers"&gt;
    &lt;insertComponent id="MapContainer" className="MapContainer"&gt;
      &lt;content type="Map" displayName="Maps"/&gt;
    &lt;/insertComponent&gt;
  &lt;/updateCategory&gt;
&lt;/categories&gt;</code></pre>

<p>
     Any DAML command can also be added to a category by using by specifying a categoryRefID in its declaration.  In this case, you can
     also use the content sub-element to define any custom data. 
     </p>
<p>
  <pre><code class="lang-csharp">&lt;button id="openMap" caption="Open" className="Controls.Cut" categoryRefID="ProjectContainers"&gt;
  &lt;content type="Map" displayName="Maps"/&gt;
&lt;/button&gt;</code></pre>

<p>
     At runtime you can use the <xref href="ArcGIS.Desktop.Framework.Categories.GetComponentElements(System.String)" data-throw-if-not-resolved="false"></xref> function to retrieve all the components registered in a particular 
     category, including DAML controls. When a <xref href="ArcGIS.Desktop.Framework.ComponentElement" data-throw-if-not-resolved="false"></xref> is returned, you can call <xref href="ArcGIS.Desktop.Framework.ComponentElement.GetContent" data-throw-if-not-resolved="false"></xref> to get a 
     Systm.DAML.Linq.XElement representing the content node or use <xref href="ArcGIS.Desktop.Framework.ComponentElement.ReadAttribute(System.String)" data-throw-if-not-resolved="false"></xref> to simply read a 
     string attribute. Call <xref href="ArcGIS.Desktop.Framework.ComponentElement.CreateComponent(System.Object%5b%5d)" data-throw-if-not-resolved="false"></xref> to instantiate a new instance of the component. Note 
     CreateComponent throws an exception when the component is referencing a DAML command.
     </p>


## Members

### GetComponentElements(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Categories.yml" sourcestartlinenumber="1">Retrieves components registered in a component category.</p>


```csharp
public static Collection<ComponentElement> GetComponentElements(string category)
```


