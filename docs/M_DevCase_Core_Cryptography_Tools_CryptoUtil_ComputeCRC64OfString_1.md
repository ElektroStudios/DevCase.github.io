# CryptoUtil.ComputeCRC64OfString Method (String, Encoding)
 

Computes a CRC-64 checksum for the specified string using the specified character encoding.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeCRC64OfString(
	string str,
	Encoding enc
)
```

**VB**<br />
``` VB
Public Shared Function ComputeCRC64OfString ( 
	str As String,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.ComputeCRC64OfString(str, 
	enc)
```

**C++**<br />
``` C++
public:
static String^ ComputeCRC64OfString(
	String^ str, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member ComputeCRC64OfString : 
        str : string * 
        enc : Encoding -> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The character Encoding.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting CRC-64 checksum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim crc64 As String = ComputeCRC64OfString("Hello World!", Encoding.ASCII)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfString">ComputeCRC64OfString Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />