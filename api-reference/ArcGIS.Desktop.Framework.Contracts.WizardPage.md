# WizardPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Represents a page inside a wizard. This is an abstract class.</p>


## Object Signature

```csharp
public abstract class WizardPage : ViewModelBase, INotifyPropertyChanged
```


## Members

### WizardPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Represents a page inside a wizard. This is an abstract class.</p>


```csharp
protected WizardPage()
```
### AllowNextIfInvalid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets and sets whether the Next button is allowed if the page is invalid.</p>


```csharp
public bool AllowNextIfInvalid { get; set; }
```
### CanJumpTo()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Override this function to control whether the wizard can jump directly to this page.</p>


```csharp
protected virtual bool CanJumpTo()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets the page's label as presented in the wizard.</p>


```csharp
public string Caption { get; set; }
```
### ClickCommand

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets the command which, when executed, causes the CurrentPage
property to reference the next page in the workflow.  If the user
is viewing the last page in the workflow, this causes the Wizard
to finish and be removed from the user interface.</p>


```csharp
public ICommand ClickCommand { get; }
```
### Data

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets or sets the data passed to the wizard.</p>


```csharp
protected object Data { get; set; }
```
### GetNextPageID()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Override this function if the page wants to override which page is next in the wizard.</p>


```csharp
protected virtual string GetNextPageID()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets the page's DAML identifier.</p>


```csharp
public string ID { get; }
```
### InvalidTooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets or sets extra information about why the page is invalid. This text appears under the tooltip. If this property is left null, a default string is presented.
To not show any supplementary tooltip set this property to an empty string.</p>


```csharp
public string InvalidTooltip { get; protected set; }
```
### IsCurrentPage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets a boolean value of true if this page is the current page.</p>


```csharp
public bool IsCurrentPage { get; }
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Override this function to indicate whether the page is valid or not.</p>


```csharp
public virtual bool IsValid { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Set this property to change if the page is displayed in the wizard or not</p>


```csharp
public bool IsVisible { get; set; }
```
### OnAllPagesInitialized()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Called when all of the wizard pages have been created and fully initialized.</p>


```csharp
public virtual void OnAllPagesInitialized()
```
### OnFinish()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Called when the wizard begins finalizing the process in order to give the page the opportunity to prevent the action (eg. unsaved changes).</p>


```csharp
public virtual Task<bool> OnFinish()
```
### OnInitialize()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Called when the page is first created to give it the opportunity to fully initialize itself. The Data member is set at this point.</p>


```csharp
protected virtual void OnInitialize()
```
### Tooltip

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.WizardPage.yml" sourcestartlinenumber="1">Gets or sets the extra information about the page appearing in a pop-up window.</p>


```csharp
public string Tooltip { get; protected set; }
```


