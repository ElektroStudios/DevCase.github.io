# ITaskbarList4.SetTabOrder Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetTabOrder(
	IntPtr hWndTab,
	IntPtr hWndInsertBefore
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetTabOrder ( 
	hWndTab As IntPtr,
	hWndInsertBefore As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWndTab As IntPtr
Dim hWndInsertBefore As IntPtr
Dim returnValue As HResult

returnValue = instance.SetTabOrder(hWndTab, 
	hWndInsertBefore)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetTabOrder(
	IntPtr hWndTab, 
	IntPtr hWndInsertBefore
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetTabOrder : 
        hWndTab : IntPtr * 
        hWndInsertBefore : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWndTab</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWndTab"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabOrder(System.IntPtr,System.IntPtr)"\]</dd><dt>hWndInsertBefore</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWndInsertBefore"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabOrder(System.IntPtr,System.IntPtr)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabOrder(System.IntPtr,System.IntPtr)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />