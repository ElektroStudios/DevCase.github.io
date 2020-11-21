# ITaskbarList4.SetProgressValue Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult SetProgressValue(
	IntPtr hWnd,
	ulong ullCompleted,
	ulong ullTotal
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function SetProgressValue ( 
	hWnd As IntPtr,
	ullCompleted As ULong,
	ullTotal As ULong
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As ITaskbarList4
Dim hWnd As IntPtr
Dim ullCompleted As ULong
Dim ullTotal As ULong
Dim returnValue As HResult

returnValue = instance.SetProgressValue(hWnd, 
	ullCompleted, ullTotal)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult SetProgressValue(
	IntPtr hWnd, 
	unsigned long long ullCompleted, 
	unsigned long long ullTotal
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract SetProgressValue : 
        hWnd : IntPtr * 
        ullCompleted : uint64 * 
        ullTotal : uint64 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressValue(System.IntPtr,System.UInt64,System.UInt64)"\]</dd><dt>ullCompleted</dt><dd>Type: System.UInt64<br />\[Missing <param name="ullCompleted"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressValue(System.IntPtr,System.UInt64,System.UInt64)"\]</dd><dt>ullTotal</dt><dd>Type: System.UInt64<br />\[Missing <param name="ullTotal"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressValue(System.IntPtr,System.UInt64,System.UInt64)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.ITaskbarList4.SetProgressValue(System.IntPtr,System.UInt64,System.UInt64)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ITaskbarList4">ITaskbarList4 Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />