# CryptoUtil.ComputeCRC64OfBytes Method 
 

Computes a CRC-64 checksum for the specified byte array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeCRC64OfBytes(
	byte[] bytes
)
```

**VB**<br />
``` VB
Public Shared Function ComputeCRC64OfBytes ( 
	bytes As Byte()
) As String
```

**VB Usage**<br />
``` VB Usage
Dim bytes As Byte()
Dim returnValue As String

returnValue = CryptoUtil.ComputeCRC64OfBytes(bytes)
```

**C++**<br />
``` C++
public:
static String^ ComputeCRC64OfBytes(
	array<unsigned char>^ bytes
)
```

**F#**<br />
``` F#
static member ComputeCRC64OfBytes : 
        bytes : byte[] -> string 

```


#### Parameters
&nbsp;<dl><dt>bytes</dt><dd>Type: System.Byte[]<br />The byte array.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting CRC-64 checksum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data as Byte() = {1, 2, 3, 4, 5}
Dim crc64 As String = ComputeCRC64OfBytes(data)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />