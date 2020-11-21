# NativeMethods.IsWow64Process Method (IntPtr, Boolean)
 

Determines whether the specified process is running under WOW64.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool IsWow64Process(
	IntPtr hProcess,
	out bool refIsWow64Process
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function IsWow64Process ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refIsWow64Process As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refIsWow64Process As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.IsWow64Process(hProcess, 
	refIsWow64Process)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool IsWow64Process(
	[InAttribute] IntPtr hProcess, 
	[OutAttribute] bool% refIsWow64Process
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member IsWow64Process : 
        hProcess : IntPtr * 
        refIsWow64Process : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refIsWow64Process</dt><dd>Type: System.Boolean<br />A pointer to a value that is set to `true` (`True` in Visual Basic) if the process is running under WOW64. If the process is running under 32-bit Windows, the value is set to `false` (`False` in Visual Basic). 

 If the process is a 64-bit application running under 64-bit Windows, the value is also set to `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `false` (`False` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/ms684139(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/ms684139(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_IsWow64Process">IsWow64Process Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />