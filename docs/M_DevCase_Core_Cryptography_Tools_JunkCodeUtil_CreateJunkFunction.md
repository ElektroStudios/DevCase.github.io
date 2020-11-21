# JunkCodeUtil.CreateJunkFunction Method 
 

Generates a junk-code function written in the specified .NET language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CreateJunkFunction(
	NetSyntaxStyle syntax,
	int parameterCount = 0
)
```

**VB**<br />
``` VB
Public Shared Function CreateJunkFunction ( 
	syntax As NetSyntaxStyle,
	Optional parameterCount As Integer = 0
) As String
```

**VB Usage**<br />
``` VB Usage
Dim syntax As NetSyntaxStyle
Dim parameterCount As Integer
Dim returnValue As String

returnValue = JunkCodeUtil.CreateJunkFunction(syntax, 
	parameterCount)
```

**C++**<br />
``` C++
public:
static String^ CreateJunkFunction(
	NetSyntaxStyle syntax, 
	int parameterCount = 0
)
```

**F#**<br />
``` F#
static member CreateJunkFunction : 
        syntax : NetSyntaxStyle * 
        ?parameterCount : int 
(* Defaults:
        let _parameterCount = defaultArg parameterCount 0
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>syntax</dt><dd>Type: <a href="T_DevCase_Interop_Managed_NetSyntaxStyle">DevCase.Interop.Managed.NetSyntaxStyle</a><br />The syntax style to use.</dd><dt>parameterCount (Optional)</dt><dd>Type: System.Int32<br />The amount of parameters to generate.</dd></dl>

#### Return Value
Type: String<br />The resulting function.

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_JunkCodeUtil">JunkCodeUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />