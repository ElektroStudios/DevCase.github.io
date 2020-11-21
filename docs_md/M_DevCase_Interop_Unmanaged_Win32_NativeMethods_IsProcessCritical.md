# NativeMethods.IsProcessCritical Method (SafeProcessHandle, Boolean)
 

Determines whether the specified process is considered critical.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool IsProcessCritical(
	SafeProcessHandle hProcess,
	ref bool refIsCritical
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function IsProcessCritical ( 
	hProcess As SafeProcessHandle,
	ByRef refIsCritical As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As SafeProcessHandle
Dim refIsCritical As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.IsProcessCritical(hProcess, 
	refIsCritical)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool IsProcessCritical(
	SafeProcessHandle^ hProcess, 
	bool% refIsCritical
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member IsProcessCritical : 
        hProcess : SafeProcessHandle * 
        refIsCritical : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: Microsoft.Win32.SafeHandles.SafeProcessHandle<br />An IntPtr to the process to query. 

 The process must have been opened with `PROCESS_QUERY_LIMITED_INFORMATION` access.</dd><dt>refIsCritical</dt><dd>Type: System.Boolean<br />A variable passed by-reference to store a value indicating whether the process is critical.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic), otherwise, `false` (`False` in Visual Basic). 

 Call GetLastWin32Error() to get specific error reason on failure.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dn386160%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dn386160%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsProcessCritical">IsProcessCritical Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />