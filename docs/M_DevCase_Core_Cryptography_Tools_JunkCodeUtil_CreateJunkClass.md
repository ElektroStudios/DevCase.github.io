# JunkCodeUtil.CreateJunkClass Method 
 

Generates a junk-code class written in the specified .NET language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CreateJunkClass(
	NetSyntaxStyle syntax,
	int blockCount = 3
)
```

**VB**<br />
``` VB
Public Shared Function CreateJunkClass ( 
	syntax As NetSyntaxStyle,
	Optional blockCount As Integer = 3
) As String
```

**VB Usage**<br />
``` VB Usage
Dim syntax As NetSyntaxStyle
Dim blockCount As Integer
Dim returnValue As String

returnValue = JunkCodeUtil.CreateJunkClass(syntax, 
	blockCount)
```

**C++**<br />
``` C++
public:
static String^ CreateJunkClass(
	NetSyntaxStyle syntax, 
	int blockCount = 3
)
```

**F#**<br />
``` F#
static member CreateJunkClass : 
        syntax : NetSyntaxStyle * 
        ?blockCount : int 
(* Defaults:
        let _blockCount = defaultArg blockCount 3
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>syntax</dt><dd>Type: <a href="T_DevCase_Interop_Managed_NetSyntaxStyle">DevCase.Interop.Managed.NetSyntaxStyle</a><br />The syntax style to use.</dd><dt>blockCount (Optional)</dt><dd>Type: System.Int32<br />The amount of method blocks to generate.</dd></dl>

#### Return Value
Type: String<br />The resulting class.

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_JunkCodeUtil">JunkCodeUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />