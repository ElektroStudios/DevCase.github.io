# CryptoUtil.EncryptFile Method (SymmetricAlgorithm, FileInfo, String)
 

Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EncryptFile(
	SymmetricAlgorithm algorithm,
	FileInfo file,
	string key
)
```

**VB**<br />
``` VB
Public Shared Sub EncryptFile ( 
	algorithm As SymmetricAlgorithm,
	file As FileInfo,
	key As String
)
```

**VB Usage**<br />
``` VB Usage
Dim algorithm As SymmetricAlgorithm
Dim file As FileInfo
Dim key As StringCryptoUtil.EncryptFile(algorithm, file, 
	key)
```

**C++**<br />
``` C++
public:
static void EncryptFile(
	SymmetricAlgorithm^ algorithm, 
	FileInfo^ file, 
	String^ key
)
```

**F#**<br />
``` F#
static member EncryptFile : 
        algorithm : SymmetricAlgorithm * 
        file : FileInfo * 
        key : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>algorithm</dt><dd>Type: System.Security.Cryptography.SymmetricAlgorithm<br />The SymmetricAlgorithm.</dd><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source file to encrypt.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.txt")
Dim key As String = "MyKey"

Dim algorithm As New DESCryptoServiceProvider()
EncryptFile(algorithm, file, key)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile">EncryptFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />