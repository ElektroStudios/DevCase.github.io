# IActiveDesktop.ApplyChanges Method 
 

Applies changes to the Active Desktop and saves them in the registry.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
int ApplyChanges(
	ActiveDesktopApplyMode applyMode
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function ApplyChanges ( 
	applyMode As ActiveDesktopApplyMode
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IActiveDesktop
Dim applyMode As ActiveDesktopApplyMode
Dim returnValue As Integer

returnValue = instance.ApplyChanges(applyMode)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
int ApplyChanges(
	ActiveDesktopApplyMode applyMode
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract ApplyChanges : 
        applyMode : ActiveDesktopApplyMode -> int 

```


#### Parameters
&nbsp;<dl><dt>applyMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ActiveDesktopApplyMode">DevCase.Interop.Unmanaged.Win32.Enums.ActiveDesktopApplyMode</a><br />A value that specifies the changes to be applied.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>, otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop">IActiveDesktop Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />