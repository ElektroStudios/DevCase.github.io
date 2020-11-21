# CryptoUtil.ComputeHashOfBytes(*T*) Method 
 

Computes a hash for the specified byte array using the given hash algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeHashOfBytes<T>(
	byte[] data
)
where T : HashAlgorithm

```

**VB**<br />
``` VB
Public Shared Function ComputeHashOfBytes(Of T As HashAlgorithm) ( 
	data As Byte()
) As String
```

**VB Usage**<br />
``` VB Usage
Dim data As Byte()
Dim returnValue As String

returnValue = CryptoUtil.ComputeHashOfBytes(data)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : HashAlgorithm
static String^ ComputeHashOfBytes(
	array<unsigned char>^ data
)
```

**F#**<br />
``` F#
static member ComputeHashOfBytes : 
        data : byte[] -> string  when 'T : HashAlgorithm

```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: System.Byte[]<br />The byte array.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The HashAlgorithm provider.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data as Byte() = {1, 2, 3, 4, 5}
Dim md5 As String = ComputeHashOfBytes(Of MD5CryptoServiceProvider)(data)
Dim sha1 As String = ComputeHashOfBytes(Of SHA1CryptoServiceProvider)(data)
Dim sha256 As String = ComputeHashOfBytes(Of SHA256CryptoServiceProvider)(data)
Dim sha384 As String = ComputeHashOfBytes(Of SHA384CryptoServiceProvider)(data)
Dim sha512 As String = ComputeHashOfBytes(Of SHA512CryptoServiceProvider)(data)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />