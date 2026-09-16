# LicenseInformation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Licensing.html">Licensing</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Provides access to the ArcGIS Pro licensing information</p>


## Object Signature

```csharp
public static class LicenseInformation
```


## Members

### CheckinLicense(LicenseCodes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Checks in a specific license code.
Applicable to concurrent use licensing only.</p>


```csharp
public static bool CheckinLicense(LicenseCodes code)
```
### CheckoutLicense(LicenseCodes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Checks out a specific license code.<br>
Applicable to concurrent use licensing only.</p>


```csharp
public static bool CheckoutLicense(LicenseCodes code)
```
### GetAvailabilityCount(LicenseCodes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Gets the number of licenses available for use. Most useful when using concurrent use licensing.</p>


```csharp
public static uint GetAvailabilityCount(LicenseCodes code)
```
### GetExpirationDate(LicenseCodes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Gets the license expiration date for the specified license code.</p>


```csharp
public static DateTime? GetExpirationDate(LicenseCodes code)
```
### IsCheckedOut(LicenseCodes)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Gets if a specific license code is checked out.</p>


```csharp
public static bool IsCheckedOut(LicenseCodes code)
```
### Level

- Kind: property

<p sourcefile="api/ArcGIS.Core.Licensing.LicenseInformation.yml" sourcestartlinenumber="1">Gets the current license level held by the user.</p>


```csharp
public static LicenseLevels Level { get; }
```


