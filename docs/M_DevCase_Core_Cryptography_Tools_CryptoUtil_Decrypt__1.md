# CryptoUtil.Decrypt(*T*) Method 
 

Decrypts a string using the specified SymmetricAlgorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Decrypt<T>(
	string str,
	string key
)
where T : SymmetricAlgorithm

```

**VB**<br />
``` VB
Public Shared Function Decrypt(Of T As SymmetricAlgorithm) ( 
	str As String,
	key As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim key As String
Dim returnValue As String

returnValue = CryptoUtil.Decrypt(str, key)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : SymmetricAlgorithm
static String^ Decrypt(
	String^ str, 
	String^ key
)
```

**F#**<br />
``` F#
static member Decrypt : 
        str : string * 
        key : string -> string  when 'T : SymmetricAlgorithm

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to decrypt.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source SymmetricAlgorithm for decryption.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Cryptography.Tools.CryptoUtil.Decrypt``1(System.String,System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
dim decrypted1 As String = Decrypt(Of DESCryptoServiceProvider)("HR6KfbLExXZ/FJrCGmB8Xg==", "MyKey") ' Result: "Hello World!"
dim decrypted2 As String = Decrypt(Of RijndaelManaged)("Pcy3lj+10sL16Actia3pCw==", "Key")            ' Result: "Hello World!"
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />