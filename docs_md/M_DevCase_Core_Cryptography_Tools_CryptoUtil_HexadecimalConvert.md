# CryptoUtil.HexadecimalConvert Method (NetSyntaxStyle, String, String)
 

Converts an Hexadecimal value to its corresponding representation in the specified language syntax.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string HexadecimalConvert(
	NetSyntaxStyle syntax,
	string value,
	string separator = ""
)
```

**VB**<br />
``` VB
Public Shared Function HexadecimalConvert ( 
	syntax As NetSyntaxStyle,
	value As String,
	Optional separator As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim syntax As NetSyntaxStyle
Dim value As String
Dim separator As String
Dim returnValue As String

returnValue = CryptoUtil.HexadecimalConvert(syntax, 
	value, separator)
```

**C++**<br />
``` C++
public:
static String^ HexadecimalConvert(
	NetSyntaxStyle syntax, 
	String^ value, 
	String^ separator = L""
)
```

**F#**<br />
``` F#
static member HexadecimalConvert : 
        syntax : NetSyntaxStyle * 
        value : string * 
        ?separator : string 
(* Defaults:
        let _separator = defaultArg separator ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>syntax</dt><dd>Type: <a href="T_DevCase_Interop_Managed_NetSyntaxStyle">DevCase.Interop.Managed.NetSyntaxStyle</a><br />The syntax style to represent the Hexadecimal value.</dd><dt>value</dt><dd>Type: System.String<br />The Hexadecimal value.</dd><dt>separator (Optional)</dt><dd>Type: System.String<br />The string used to separate Hexadecimal sequences.</dd></dl>

#### Return Value
Type: String<br />The resulting value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td>style</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As String = HexadecimalConvert(HexadecimalStyle.CSharp, "48 65 6C 6C 6F 20 57")
Dim value As String = HexadecimalConvert(HexadecimalStyle.VbNet, "48 65 6C 6C 6F 20 57")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalConvert">HexadecimalConvert Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />