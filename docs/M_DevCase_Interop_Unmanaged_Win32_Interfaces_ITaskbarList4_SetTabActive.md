# ITaskbarList4.SetTabActive Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetTabActive(
	IntPtr hWndTab,
	IntPtr hWndInsertBefore,
	uint dwReserved
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetTabActive ( 
	hWndTab As IntPtr,
	hWndInsertBefore As IntPtr,
	dwReserved As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWndTab As IntPtr
Dim hWndInsertBefore As IntPtr
Dim dwReserved As UInteger
Dim returnValue As HResult

returnValue = instance.SetTabActive(hWndTab, 
	hWndInsertBefore, dwReserved)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetTabActive(
	IntPtr hWndTab, 
	IntPtr hWndInsertBefore, 
	unsigned int dwReserved
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetTabActive : 
        hWndTab : IntPtr * 
        hWndInsertBefore : IntPtr * 
        dwReserved : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWndTab</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWndTab"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabActive(System.IntPtr,System.IntPtr,System.UInt32)"\]</dd><dt>hWndInsertBefore</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWndInsertBefore"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabActive(System.IntPtr,System.IntPtr,System.UInt32)"\]</dd><dt>dwReserved</dt><dd>Type: System.UInt32<br />\[Missing <param name="dwReserved"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabActive(System.IntPtr,System.IntPtr,System.UInt32)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetTabActive(System.IntPtr,System.IntPtr,System.UInt32)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />