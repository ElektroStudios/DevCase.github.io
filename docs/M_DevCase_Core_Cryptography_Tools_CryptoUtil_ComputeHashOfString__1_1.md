# CryptoUtil.ComputeHashOfString(*T*) Method (String, Encoding)
 

Computes a hash for the specified string using the given hash algorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeHashOfString<T>(
	string str,
	Encoding enc
)
where T : HashAlgorithm

```

**VB**<br />
``` VB
Public Shared Function ComputeHashOfString(Of T As HashAlgorithm) ( 
	str As String,
	enc As Encoding
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim enc As Encoding
Dim returnValue As String

returnValue = CryptoUtil.ComputeHashOfString(str, 
	enc)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : HashAlgorithm
static String^ ComputeHashOfString(
	String^ str, 
	Encoding^ enc
)
```

**F#**<br />
``` F#
static member ComputeHashOfString : 
        str : string * 
        enc : Encoding -> string  when 'T : HashAlgorithm

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The character Encoding.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The HashAlgorithm provider.</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim md5 As String = ComputeHashOfString(Of MD5CryptoServiceProvider)("Hello World!", Encoding.ASCII)
Dim sha1 As String = ComputeHashOfString(Of SHA1CryptoServiceProvider)("Hello World!", Encoding.ASCII)
Dim sha256 As String = ComputeHashOfString(Of SHA256CryptoServiceProvider)("Hello World!", Encoding.ASCII)
Dim sha384 As String = ComputeHashOfString(Of SHA384CryptoServiceProvider)("Hello World!", Encoding.ASCII)
Dim sha512 As String = ComputeHashOfString(Of SHA512CryptoServiceProvider)("Hello World!", Encoding.ASCII)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfString">ComputeHashOfString Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />