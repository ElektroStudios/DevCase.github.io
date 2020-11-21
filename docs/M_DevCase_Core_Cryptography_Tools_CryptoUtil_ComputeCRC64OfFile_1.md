# CryptoUtil.ComputeCRC64OfFile Method (String)
 

Computes a CRC-64 checksum for the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeCRC64OfFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function ComputeCRC64OfFile ( 
	filepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As String

returnValue = CryptoUtil.ComputeCRC64OfFile(filepath)
```

**C++**<br />
``` C++
public:
static String^ ComputeCRC64OfFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member ComputeCRC64OfFile : 
        filepath : string -> string 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting CRC-64 checksum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim crc64 As String = ComputeCRC64OfFile("C:\File.ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfFile">ComputeCRC64OfFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />