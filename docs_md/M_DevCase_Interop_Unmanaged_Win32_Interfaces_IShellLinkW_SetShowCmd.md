# IShellLinkW.SetShowCmd Method 
 

Sets the show command for a Shell link object. 

 The show command sets the initial show state of the window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetShowCmd(
	NativeWindowState windowState
)
```

**VB**<br />
``` VB
Sub SetShowCmd ( 
	windowState As NativeWindowState
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim windowState As NativeWindowState

instance.SetShowCmd(windowState)
```

**C++**<br />
``` C++
void SetShowCmd(
	NativeWindowState windowState
)
```

**F#**<br />
``` F#
abstract SetShowCmd : 
        windowState : NativeWindowState -> unit 

```


#### Parameters
&nbsp;<dl><dt>windowState</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">NativeWindowState</a> flags.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />