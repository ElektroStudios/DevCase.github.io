# NativeMethods.EndUpdateResource Method (IntPtr, Boolean)
 

Commits or discards changes made prior to a call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a> function. 

 Before you call this function, make sure all file handles other than the one returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginUpdateResource">BeginUpdateResource(String, Boolean)</a> are closed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool EndUpdateResource(
	IntPtr hUpdate,
	bool discard
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function EndUpdateResource ( 
	hUpdate As IntPtr,
	discard As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hUpdate As IntPtr
Dim discard As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.EndUpdateResource(hUpdate, 
	discard)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool EndUpdateResource(
	IntPtr hUpdate, 
	bool discard
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member EndUpdateResource : 
        hUpdate : IntPtr * 
        discard : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hUpdate</dt><dd>Type: System.IntPtr<br />A module handle returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BeginUpdateResource">BeginUpdateResource(String, Boolean)</a> function, and used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_UpdateResource">UpdateResource(SafeModuleHandle, ResourceType, IntPtr, UInt16, IntPtr, UInt32)</a>, referencing the file to be updated.</dd><dt>discard</dt><dd>Type: System.Boolean<br />Indicates whether to write the resource updates to the file. 

 If this parameter is `true` (`True` in Visual Basic), no changes are made. 

 If it is `false` (`False` in Visual Basic), the changes are made: the resource updates will take effect.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the function succeeds; `false` (`False` in Visual Basic) otherwise. 

 If the function succeeds and *discard* parameter is `true` (`True` in Visual Basic), then no resource updates are made to the file; otherwise all successful resource updates are made to the file. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648032(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648032(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EndUpdateResource">EndUpdateResource Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />