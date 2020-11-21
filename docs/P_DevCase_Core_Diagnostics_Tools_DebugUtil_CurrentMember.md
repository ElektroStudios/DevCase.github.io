# DebugUtil.CurrentMember Property 
 

Gets the current executing member in the stack trace of the application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static MethodBase CurrentMember { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property CurrentMember As MethodBase
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As MethodBase

value = DebugUtil.CurrentMember

```

**C++**<br />
``` C++
public:
static property MethodBase^ CurrentMember {
	MethodBase^ get ();
}
```

**F#**<br />
``` F#
static member CurrentMember : MethodBase with get

```


#### Property Value
Type: MethodBase<br />The current executing member.

## Examples
This is a code example. 
**VB**<br />
``` VB
Private Sub TestMethod()

   MsgBox(CurrentMember.Name)

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />