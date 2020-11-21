# Filesize.Size Property (SizeUnits, Int32, NumberFormatInfo)
 

Gets the filesize, in the specified unit of size, using the specified numeric format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	SizeUnits sizeUnit,
	int decimalPrecision,
	NumberFormatInfo numberFormatInfo = null
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Size ( 
	sizeUnit As SizeUnits,
	decimalPrecision As Integer,
	Optional numberFormatInfo As NumberFormatInfo = Nothing
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As Filesize
Dim sizeUnit As SizeUnits
Dim decimalPrecision As Integer
Dim numberFormatInfo As NumberFormatInfo
Dim value As String

value = instance.Size(sizeUnit, decimalPrecision, 
	numberFormatInfo)

```

**C++**<br />
``` C++
public:
property String^ Size[SizeUnits sizeUnit, int decimalPrecision, NumberFormatInfo^ numberFormatInfo = nullptr] {
	String^ get (SizeUnits sizeUnit, int decimalPrecision, NumberFormatInfo^ numberFormatInfo = nullptr);
}
```

**F#**<br />
``` F#
member Size : string with get

```


#### Parameters
&nbsp;<dl><dt>sizeUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />The unit of size.</dd><dt>decimalPrecision</dt><dd>Type: System.Int32<br /></dd><dt>numberFormatInfo (Optional)</dt><dd>Type: System.Globalization.NumberFormatInfo<br />A custom NumberFormatInfo format provider.</dd></dl>

#### Property Value
Type: String<br />The filesize.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Filesize">Filesize Class</a><br /><a href="Overload_DevCase_Core_IO_Filesize_Size">Size Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />