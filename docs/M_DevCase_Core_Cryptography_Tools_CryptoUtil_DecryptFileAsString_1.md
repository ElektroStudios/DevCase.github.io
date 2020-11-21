# CryptoUtil.DecryptFileAsString Method (SymmetricAlgorithm, String, String)
 

Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DecryptFileAsString(
	SymmetricAlgorithm algorithm,
	string srcFilepath,
	string key
)
```

**VB**<br />
``` VB
Public Shared Function DecryptFileAsString ( 
	algorithm As SymmetricAlgorithm,
	srcFilepath As String,
	key As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim algorithm As SymmetricAlgorithm
Dim srcFilepath As String
Dim key As String
Dim returnValue As String

returnValue = CryptoUtil.DecryptFileAsString(algorithm, 
	srcFilepath, key)
```

**C++**<br />
``` C++
public:
static String^ DecryptFileAsString(
	SymmetricAlgorithm^ algorithm, 
	String^ srcFilepath, 
	String^ key
)
```

**F#**<br />
``` F#
static member DecryptFileAsString : 
        algorithm : SymmetricAlgorithm * 
        srcFilepath : string * 
        key : string -> string 

```


#### Parameters
&nbsp;<dl><dt>algorithm</dt><dd>Type: System.Security.Cryptography.SymmetricAlgorithm<br />The SymmetricAlgorithm.</dd><dt>srcFilepath</dt><dd>Type: System.String<br />The source filepath.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Cryptography.Tools.CryptoUtil.DecryptFileAsString(System.Security.Cryptography.SymmetricAlgorithm,System.String,System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim srcFile As New FileInfo("C:\Encrypted.txt")
Dim key As String = "MyKey"

Dim algorithm As New DESCryptoServiceProvider()
Dim decrypted As String = DecryptFileAsString(algorithm, srcFile.FullName, key)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString">DecryptFileAsString Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />