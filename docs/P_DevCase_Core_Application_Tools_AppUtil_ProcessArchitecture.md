# AppUtil.ProcessArchitecture Property 
 

Determines whether the architecture of the current process is 32 or 64 Bits.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ProcessArchitecture ProcessArchitecture { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProcessArchitecture As ProcessArchitecture
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ProcessArchitecture

value = AppUtil.ProcessArchitecture

```

**C++**<br />
``` C++
public:
static property ProcessArchitecture ProcessArchitecture {
	ProcessArchitecture get ();
}
```

**F#**<br />
``` F#
static member ProcessArchitecture : ProcessArchitecture with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_ProcessArchitecture">ProcessArchitecture</a><br />An ProcessArchitecture object that specifies the architecture of the current process.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim arch As ProcessArchitecture = CurrentArchitecture
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />