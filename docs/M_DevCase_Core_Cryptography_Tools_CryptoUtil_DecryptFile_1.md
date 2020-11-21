# CryptoUtil.DecryptFile Method (SymmetricAlgorithm, String, String, String)
 

Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DecryptFile(
	SymmetricAlgorithm algorithm,
	string srcFilepath,
	string dstFilepath,
	string key
)
```

**VB**<br />
``` VB
Public Shared Sub DecryptFile ( 
	algorithm As SymmetricAlgorithm,
	srcFilepath As String,
	dstFilepath As String,
	key As String
)
```

**VB Usage**<br />
``` VB Usage
Dim algorithm As SymmetricAlgorithm
Dim srcFilepath As String
Dim dstFilepath As String
Dim key As StringCryptoUtil.DecryptFile(algorithm, srcFilepath, 
	dstFilepath, key)
```

**C++**<br />
``` C++
public:
static void DecryptFile(
	SymmetricAlgorithm^ algorithm, 
	String^ srcFilepath, 
	String^ dstFilepath, 
	String^ key
)
```

**F#**<br />
``` F#
static member DecryptFile : 
        algorithm : SymmetricAlgorithm * 
        srcFilepath : string * 
        dstFilepath : string * 
        key : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>algorithm</dt><dd>Type: System.Security.Cryptography.SymmetricAlgorithm<br />The SymmetricAlgorithm.</dd><dt>srcFilepath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>dstFilepath</dt><dd>Type: System.String<br />The destination filepath.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcFile As New FileInfo("C:\Encrypted.txt")
Dim dstFile As New FileInfo("C:\Decrypted.txt")
Dim key As String = "MyKey"

Dim algorithm As New DESCryptoServiceProvider()
DecryptFile(algorithm, srcFile.FullName, dstFile.FullName, key)
' srcFile.Delete()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile">DecryptFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />