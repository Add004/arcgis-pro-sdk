# Spinner

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Spinner.yml" sourcestartlinenumber="1">Represents a control that can be used to display and edit doubles. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class Spinner : PlugIn, INotifyPropertyChanged
```

## Remarks

<p>
    Spinners edit doubles like an edit box except they additionally provide increment and decrement buttons and support a range 
    established with the minimum and maximum attributes. In DAML you can also specify a default value and an increment value. Use the format attribute to 
    specify how to display the double. For example, use 'C' to present a currency or F4 for a double with 4 decimals. In addition, use the suffix attribute
    to tag on a trailing string such as a '%' sign.
    </p>
<p>
    Spinners do not support delay loading with loadOnClick, they are instantiated when they become visible.
    </p>
<p>
  <table><thead><tr><th class="term">DAML attributes</th></tr></thead><tbody><tr><td class="term">assembly</td><td class="description">Assembly name if not in the default assembly.</td></tr><tr><td class="term">caption</td><td class="description">The heading.</td></tr><tr><td class="term">categoryRefID</td><td class="description">Adds control to a specific component category.</td></tr><tr><td class="term">className</td><td class="description">Required class identifier. Optionally include namespace if not in default namespace.</td></tr><tr><td class="term">condition</td><td class="description">Automatically disable the button if the condition is not satisfied.</td></tr><tr><td class="term">defaultValue</td><td class="description">The initial value.</td></tr><tr><td class="term">disableIfBusy</td><td class="description">Automatically disable the button if the application is busy. Default true.</td></tr><tr><td class="term">extendedCaption</td><td class="description">A more descriptive title.</td></tr><tr><td class="term">format</td><td class="description">The double format string, e.g. 'C' for currency and F4 to show 4 decimal places. Default is F2.</td></tr><tr><td class="term">helpContextID</td><td class="description">The help topic to show.</td></tr><tr><td class="term">id</td><td class="description">Required identifier.</td></tr><tr><td class="term">image</td><td class="description">Image (16x16) used when spinner is middle and large sized.</td></tr><tr><td class="term">increment</td><td class="description">The amount to add and subtract to the value when the increment and decrement buttons are clicked. Default is 1.0.</td></tr><tr><td class="term">maximum</td><td class="description">The maximum value.</td></tr><tr><td class="term">minimum</td><td class="description">The minimum value.</td></tr><tr><td class="term">publicKeyToken</td><td class="description">The necessary public key token if the assembly is strongly named.</td></tr><tr><td class="term">suffix</td><td class="description">Trailing string such as '%'.</td></tr><tr><td class="term">version</td><td class="description">The version of the dll if the assembly is strongly named.</td></tr><tr><td class="term">width</td><td class="description">The width of the control.</td></tr></tbody></table>



## Members

### OnValueChanged(double?)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Spinner.yml" sourcestartlinenumber="1">Invoked whenever the value changes.</p>


```csharp
protected virtual void OnValueChanged(double? value)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.Spinner.yml" sourcestartlinenumber="1">Gets or sets the value.</p>


```csharp
public double? Value { get; set; }
```


