# ConsoleProgressBar Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ConsoleProgressBar(
	int blockCount = 10
)
```

**VB**<br />
``` VB
Public Sub New ( 
	Optional blockCount As Integer = 10
)
```

**VB Usage**<br />
``` VB Usage
Dim blockCount As Integer

Dim instance As New ConsoleProgressBar(blockCount)
```

**C++**<br />
``` C++
public:
ConsoleProgressBar(
	int blockCount = 10
)
```

**F#**<br />
``` F#
new : 
        ?blockCount : int 
(* Defaults:
        let _blockCount = defaultArg blockCount 10
*)
-> ConsoleProgressBar
```


#### Parameters
&nbsp;<dl><dt>blockCount (Optional)</dt><dd>Type: System.Int32<br />The amount of blocks to display in the progress bar. Default value is: 20</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />