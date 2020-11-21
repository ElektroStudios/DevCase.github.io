# CryptoUtil.ComputeHashOfFile(*T*) Method (String)
 

Computes a hash for the specified file using the given hash algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeHashOfFile<T>(
	string filepath
)
where T : HashAlgorithm

```

**VB**<br />
``` VB
Public Shared Function ComputeHashOfFile(Of T As HashAlgorithm) ( 
	filepath As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As String

returnValue = CryptoUtil.ComputeHashOfFile(filepath)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : HashAlgorithm
static String^ ComputeHashOfFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member ComputeHashOfFile : 
        filepath : string -> string  when 'T : HashAlgorithm

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The filepath.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The HashAlgorithm provider.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim md5 As String = ComputeHashOfFile(Of MD5CryptoServiceProvider)("C:\File.ext")
Dim sha1 As String = ComputeHashOfFile(Of SHA1CryptoServiceProvider)("C:\File.ext")
Dim sha256 As String = ComputeHashOfFile(Of SHA256CryptoServiceProvider)("C:\File.ext")
Dim sha384 As String = ComputeHashOfFile(Of SHA384CryptoServiceProvider)("C:\File.ext")
Dim sha512 As String = ComputeHashOfFile(Of SHA512CryptoServiceProvider)("C:\File.ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfFile">ComputeHashOfFile Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />