# CryptoUtil.ComputeCRC64OfFile Method (FileInfo)
 

Computes a CRC-64 checksum for the specified file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeCRC64OfFile(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function ComputeCRC64OfFile ( 
	file As FileInfo
) As String
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As String

returnValue = CryptoUtil.ComputeCRC64OfFile(file)
```

**C++**<br />
``` C++
public:
static String^ ComputeCRC64OfFile(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member ComputeCRC64OfFile : 
        file : FileInfo -> string 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The file.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting CRC-64 checksum.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim crc64 As String = ComputeCRC64OfFile(New FileInfo("C:\File.ext"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfFile">ComputeCRC64OfFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />