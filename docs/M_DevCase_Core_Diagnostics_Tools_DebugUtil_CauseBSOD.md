# DebugUtil.CauseBSOD Method 
 

Causes a BSOD (Blue Screen of Death). 

 Please be aware that after causing the BSOD, the operating system will stop responding and a computer shutdown/restart will be required.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void CauseBSOD(
	NTStatus errorCode = NTStatus.ASSERTION_FAILURE
)
```

**VB**<br />
``` VB
Public Shared Sub CauseBSOD ( 
	Optional errorCode As NTStatus = NTStatus.ASSERTION_FAILURE
)
```

**VB Usage**<br />
``` VB Usage
Dim errorCode As NTStatusDebugUtil.CauseBSOD(errorCode)
```

**C++**<br />
``` C++
public:
static void CauseBSOD(
	NTStatus errorCode = NTStatus::ASSERTION_FAILURE
)
```

**F#**<br />
``` F#
static member CauseBSOD : 
        ?errorCode : NTStatus 
(* Defaults:
        let _errorCode = defaultArg errorCode NTStatus.ASSERTION_FAILURE
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>errorCode (Optional)</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">DevCase.Interop.Unmanaged.Win32.Enums.NTStatus</a><br />\[Missing <param name="errorCode"/> documentation for "M:DevCase.Core.Diagnostics.Tools.DebugUtil.CauseBSOD(DevCase.Interop.Unmanaged.Win32.Enums.NTStatus)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />