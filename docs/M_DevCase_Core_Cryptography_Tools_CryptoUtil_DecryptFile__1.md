# CryptoUtil.DecryptFile(*T*) Method (FileInfo, FileInfo, String)
 

Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DecryptFile<T>(
	FileInfo srcFile,
	FileInfo dstFile,
	string key
)
where T : SymmetricAlgorithm

```

**VB**<br />
``` VB
Public Shared Sub DecryptFile(Of T As SymmetricAlgorithm) ( 
	srcFile As FileInfo,
	dstFile As FileInfo,
	key As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFile As FileInfo
Dim dstFile As FileInfo
Dim key As StringCryptoUtil.DecryptFile(srcFile, dstFile, 
	key)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : SymmetricAlgorithm
static void DecryptFile(
	FileInfo^ srcFile, 
	FileInfo^ dstFile, 
	String^ key
)
```

**F#**<br />
``` F#
static member DecryptFile : 
        srcFile : FileInfo * 
        dstFile : FileInfo * 
        key : string -> unit  when 'T : SymmetricAlgorithm

```


#### Parameters
&nbsp;<dl><dt>srcFile</dt><dd>Type: System.IO.FileInfo<br />The source file.</dd><dt>dstFile</dt><dd>Type: System.IO.FileInfo<br />The destination file.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of SymmetricAlgorithm for decryption.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcFile As New FileInfo("C:\Encrypted.txt")
Dim dstFile As New FileInfo("C:\Decrypted.txt")
Dim key As String = "MyKey"

DecryptFile(Of DESCryptoServiceProvider)(srcFile, dstFile, key)
' srcFile.Delete()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile">DecryptFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />