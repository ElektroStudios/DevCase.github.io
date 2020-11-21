# CryptoUtil.EncryptFile Method (SymmetricAlgorithm, FileInfo, FileInfo, String)
 

Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to a destination file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EncryptFile(
	SymmetricAlgorithm algorithm,
	FileInfo srcFile,
	FileInfo dstFile,
	string key
)
```

**VB**<br />
``` VB
Public Shared Sub EncryptFile ( 
	algorithm As SymmetricAlgorithm,
	srcFile As FileInfo,
	dstFile As FileInfo,
	key As String
)
```

**VB Usage**<br />
``` VB Usage
Dim algorithm As SymmetricAlgorithm
Dim srcFile As FileInfo
Dim dstFile As FileInfo
Dim key As StringCryptoUtil.EncryptFile(algorithm, srcFile, 
	dstFile, key)
```

**C++**<br />
``` C++
public:
static void EncryptFile(
	SymmetricAlgorithm^ algorithm, 
	FileInfo^ srcFile, 
	FileInfo^ dstFile, 
	String^ key
)
```

**F#**<br />
``` F#
static member EncryptFile : 
        algorithm : SymmetricAlgorithm * 
        srcFile : FileInfo * 
        dstFile : FileInfo * 
        key : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>algorithm</dt><dd>Type: System.Security.Cryptography.SymmetricAlgorithm<br />The SymmetricAlgorithm.</dd><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>dstFile</dt><dd>Type: System.IO.FileInfo<br />The destination file.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcFile As New FileInfo("C:\File.txt")
Dim dstFile As New FileInfo(String.Format("{0}.bin", srcFile.FullName))
Dim key As String = "MyKey"

Dim algorithm As New DESCryptoServiceProvider()
EncryptFile(algorithm, srcFile, dstFile, key)
' srcFile.Delete()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile">EncryptFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />