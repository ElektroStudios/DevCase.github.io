# Filesize.SizeRounded Property (Int32, NumberFormatInfo)
 

Gets the filesize, rounded using the most approximated unit of size, with the specified decimal precision.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string this[
	int decimalPrecision,
	NumberFormatInfo numberFormatInfo = null
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property SizeRounded ( 
	decimalPrecision As Integer,
	Optional numberFormatInfo As NumberFormatInfo = Nothing
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As Filesize
Dim decimalPrecision As Integer
Dim numberFormatInfo As NumberFormatInfo
Dim value As String

value = instance.SizeRounded(decimalPrecision, 
	numberFormatInfo)

```

**C++**<br />
``` C++
public:
property String^ SizeRounded[int decimalPrecision, NumberFormatInfo^ numberFormatInfo = nullptr] {
	String^ get (int decimalPrecision, NumberFormatInfo^ numberFormatInfo = nullptr);
}
```

**F#**<br />
``` F#
member SizeRounded : string with get

```


#### Parameters
&nbsp;<dl><dt>decimalPrecision</dt><dd>Type: System.Int32<br />The decimal precision.</dd><dt>numberFormatInfo (Optional)</dt><dd>Type: System.Globalization.NumberFormatInfo<br />A NumberFormatInfo format provider.</dd></dl>

#### Property Value
Type: String<br />The rounded value, with the specified decimal precision.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Filesize">Filesize Class</a><br /><a href="Overload_DevCase_Core_IO_Filesize_SizeRounded">SizeRounded Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />