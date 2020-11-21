# CryptoUtil.DecryptFileAsString(*T*) Method (String, String)
 

Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DecryptFileAsString<T>(
	string srcFilepath,
	string key
)
where T : SymmetricAlgorithm

```

**VB**<br />
``` VB
Public Shared Function DecryptFileAsString(Of T As SymmetricAlgorithm) ( 
	srcFilepath As String,
	key As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim srcFilepath As String
Dim key As String
Dim returnValue As String

returnValue = CryptoUtil.DecryptFileAsString(srcFilepath, 
	key)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : SymmetricAlgorithm
static String^ DecryptFileAsString(
	String^ srcFilepath, 
	String^ key
)
```

**F#**<br />
``` F#
static member DecryptFileAsString : 
        srcFilepath : string * 
        key : string -> string  when 'T : SymmetricAlgorithm

```


#### Parameters
&nbsp;<dl><dt>srcFilepath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of SymmetricAlgorithm for decryption.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Cryptography.Tools.CryptoUtil.DecryptFileAsString``1(System.String,System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcFile As New FileInfo("C:\Encrypted.txt")
Dim key As String = "MyKey"

Dim decrypted As String = DecryptFileAsString(Of DESCryptoServiceProvider)(srcFile.FullName, key)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString">DecryptFileAsString Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />