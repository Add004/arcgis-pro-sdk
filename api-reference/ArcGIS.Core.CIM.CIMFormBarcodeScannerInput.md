# CIMFormBarcodeScannerInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Represents a barcode or QR code scanner form input. If the client does not support
barcode scanning, a single-line text box should be used.</p>


## Object Signature

```csharp
public class CIMFormBarcodeScannerInput : CIMFormInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormBarcodeScannerInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Represents a barcode or QR code scanner form input. If the client does not support
barcode scanning, a single-line text box should be used.</p>


```csharp
public CIMFormBarcodeScannerInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormBarcodeScannerInput.</p>


```csharp
public CIMFormBarcodeScannerInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormBarcodeScannerInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormBarcodeScannerInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Gets or sets the maximum number of characters allowed. This only applies for string fields.
If set (or defaulted) to -1, the value is derived from the length property of the referenced field
in the service.</p>


```csharp
public long MaxLength { get; set; }
```
### MinLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Gets or sets the minimum number of characters allowed. This only applies for string fields.
If set (or defaulted) to 0, there is no minimum constraint.</p>


```csharp
public long MinLength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormBarcodeScannerInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormBarcodeScannerInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


