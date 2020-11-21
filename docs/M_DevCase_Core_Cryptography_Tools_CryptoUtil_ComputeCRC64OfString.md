# CryptoUtil.ComputeCRC64OfString Method (String)
 

Computes a CRC-64 checksum for the specified ASCII string.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeCRC64OfString(
	string str
)
```

**VB**<br />
``` VB
Public Shared Function ComputeCRC64OfString ( 
	str As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As String

returnValue = CryptoUtil.ComputeCRC64OfString(str)
```

**C++**<br />
``` C++
public:
static String^ ComputeCRC64OfString(
	String^ str
)
```

**F#**<br />
``` F#
static member ComputeCRC64OfString : 
        str : string -> string 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting CRC-64 checksum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim crc64 As String = ComputeCRC64OfString("Hello World!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfString">ComputeCRC64OfString Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />