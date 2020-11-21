# ITaskbarList4.SetProgressState Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetProgressState(
	IntPtr hWnd,
	TaskbarProgressBarState tbpFlags
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetProgressState ( 
	hWnd As IntPtr,
	tbpFlags As TaskbarProgressBarState
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWnd As IntPtr
Dim tbpFlags As TaskbarProgressBarState
Dim returnValue As HResult

returnValue = instance.SetProgressState(hWnd, 
	tbpFlags)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetProgressState(
	IntPtr hWnd, 
	TaskbarProgressBarState tbpFlags
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetProgressState : 
        hWnd : IntPtr * 
        tbpFlags : TaskbarProgressBarState -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressState(System.IntPtr,DevCase.Interop.Unmanaged.Win32.Enums.TaskbarProgressBarState)"\]</dd><dt>tbpFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TaskbarProgressBarState">DevCase.Interop.Unmanaged.Win32.Enums.TaskbarProgressBarState</a><br />\[Missing <param name="tbpFlags"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressState(System.IntPtr,DevCase.Interop.Unmanaged.Win32.Enums.TaskbarProgressBarState)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressState(System.IntPtr,DevCase.Interop.Unmanaged.Win32.Enums.TaskbarProgressBarState)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />