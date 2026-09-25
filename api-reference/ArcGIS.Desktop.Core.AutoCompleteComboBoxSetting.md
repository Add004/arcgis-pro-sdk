# AutoCompleteComboBoxSetting

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Represents an object to configure <xref href="ArcGIS.Desktop.Core.AutoCompleteComboBox" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class AutoCompleteComboBoxSetting
```


## Members

### AutoCompleteComboBoxSetting()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Represents an object to configure <xref href="ArcGIS.Desktop.Core.AutoCompleteComboBox" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AutoCompleteComboBoxSetting()
```
### Default

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Gets the default setting.</p>


```csharp
public static AutoCompleteComboBoxSetting Default { get; set; }
```
### Delay

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Gets the duration to delay updating the suggestion list.
Returns <code>Zero</code> if no delay.
Default: 300ms.</p>


```csharp
public virtual TimeSpan Delay { get; }
```
### GetFilter(string, Func&lt;object, string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Gets a filter function which determines whether items should be suggested or not
for the specified query.
Default: Gets the filter which maps an item to <code>true</code>
if its text contains the query (case insensitive).</p>


```csharp
public virtual Predicate<object> GetFilter(string query, Func<object, string> stringFromItem)
```
### MaxSuggestionCount

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.AutoCompleteComboBoxSetting.yml" sourcestartlinenumber="1">Gets an integer.
The combobox opens the drop down
if the number of suggested items is less than the value.
Note that the value is larger, it's heavier to open the drop down.
Default: 100.</p>


```csharp
public virtual int MaxSuggestionCount { get; }
```


