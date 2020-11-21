# CryptoUtil.EncryptFile(*T*) Method (String, String)
 

Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EncryptFile<T>(
	string srcFilepath,
	string key
)
where T : SymmetricAlgorithm

```

**VB**<br />
``` VB
Public Shared Sub EncryptFile(Of T As SymmetricAlgorithm) ( 
	srcFilepath As String,
	key As String
)
```

**VB Usage**<br />
``` VB Usage
Dim srcFilepath As String
Dim key As StringCryptoUtil.EncryptFile(srcFilepath, key)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : SymmetricAlgorithm
static void EncryptFile(
	String^ srcFilepath, 
	String^ key
)
```

**F#**<br />
``` F#
static member EncryptFile : 
        srcFilepath : string * 
        key : string -> unit  when 'T : SymmetricAlgorithm

```


#### Parameters
&nbsp;<dl><dt>srcFilepath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of SymmetricAlgorithm for encryption.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.txt")
Dim key As String = "MyKey"

EncryptFile(Of DESCryptoServiceProvider)(file.FullName, key)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile">EncryptFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />