# JunkCodeUtil.CreateJunkModule Method 
 

Generates a junk-code module.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CreateJunkModule(
	int blockCount = 3
)
```

**VB**<br />
``` VB
Public Shared Function CreateJunkModule ( 
	Optional blockCount As Integer = 3
) As String
```

**VB Usage**<br />
``` VB Usage
Dim blockCount As Integer
Dim returnValue As String

returnValue = JunkCodeUtil.CreateJunkModule(blockCount)
```

**C++**<br />
``` C++
public:
static String^ CreateJunkModule(
	int blockCount = 3
)
```

**F#**<br />
``` F#
static member CreateJunkModule : 
        ?blockCount : int 
(* Defaults:
        let _blockCount = defaultArg blockCount 3
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>blockCount (Optional)</dt><dd>Type: System.Int32<br />The amount of method blocks to generate.</dd></dl>

#### Return Value
Type: String<br />The resulting module.

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_JunkCodeUtil">JunkCodeUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />