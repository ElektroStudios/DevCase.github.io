# IShellLinkW.GetShowCmd Method 
 

Retrieves the ShowWindowFlags for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetShowCmd(
	ref NativeWindowState refWindowState
)
```

**VB**<br />
``` VB
Sub GetShowCmd ( 
	ByRef refWindowState As NativeWindowState
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim refWindowState As NativeWindowState

instance.GetShowCmd(refWindowState)
```

**C++**<br />
``` C++
void GetShowCmd(
	NativeWindowState% refWindowState
)
```

**F#**<br />
``` F#
abstract GetShowCmd : 
        refWindowState : NativeWindowState byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refWindowState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">NativeWindowState</a> Flags.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />