# CryptoUtil.Encrypt(*T*) Method 
 

Encrypts a string using the specified SymmetricAlgorithm.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string Encrypt<T>(
	string str,
	string key
)
where T : SymmetricAlgorithm

```

**VB**<br />
``` VB
Public Shared Function Encrypt(Of T As SymmetricAlgorithm) ( 
	str As String,
	key As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim key As String
Dim returnValue As String

returnValue = CryptoUtil.Encrypt(str, key)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : SymmetricAlgorithm
static String^ Encrypt(
	String^ str, 
	String^ key
)
```

**F#**<br />
``` F#
static member Encrypt : 
        str : string * 
        key : string -> string  when 'T : SymmetricAlgorithm

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The string to encrypt.</dd><dt>key</dt><dd>Type: System.String<br />The key.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The source SymmetricAlgorithm for encryption.</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Cryptography.Tools.CryptoUtil.Encrypt``1(System.String,System.String)"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>key</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
dim encrypted1 As String = Encrypt(Of AesCryptoServiceProvider)("Hello World!", "MyKey")
dim encrypted2 As String = Encrypt(Of RijndaelManaged)("Hello World!", "MyKey")
dim encrypted3 As String = Encrypt(Of DESCryptoServiceProvider)("Hello World!", "MyKey")
dim encrypted4 As String = Encrypt(Of TripleDESCryptoServiceProvider)("Hello World!", "MyKey")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />