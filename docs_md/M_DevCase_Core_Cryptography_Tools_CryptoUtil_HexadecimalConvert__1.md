# CryptoUtil.HexadecimalConvert(*T*) Method (String, String)
 

Converts an Hexadecimal value to its corresponding representation of the specified Type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T HexadecimalConvert<T>(
	string value,
	string separator = ""
)

```

**VB**<br />
``` VB
Public Shared Function HexadecimalConvert(Of T) ( 
	value As String,
	Optional separator As String = ""
) As T
```

**VB Usage**<br />
``` VB Usage
Dim value As String
Dim separator As String
Dim returnValue As T

returnValue = CryptoUtil.HexadecimalConvert(value, 
	separator)
```

**C++**<br />
``` C++
public:
generic<typename T>
static T HexadecimalConvert(
	String^ value, 
	String^ separator = L""
)
```

**F#**<br />
``` F#
static member HexadecimalConvert : 
        value : string * 
        ?separator : string 
(* Defaults:
        let _separator = defaultArg separator ""
*)
-> 'T 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.String<br />The Hexadecimal value.</dd><dt>separator (Optional)</dt><dd>Type: System.String<br />The string used to separate Hexadecimal sequences.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The datatype. 

 Only Byte, SByte, Int16, UInt16Int32, UInt32, Int64 ans UInt64 are supported.</dd></dl>

#### Return Value
Type: *T*<br />The resulting value.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Not a valid datatype.;T</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value As Integer = HexadecimalConvert(Of Integer)("0x0200")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_CryptoUtil">CryptoUtil Class</a><br /><a href="Overload_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalConvert">HexadecimalConvert Overload</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />