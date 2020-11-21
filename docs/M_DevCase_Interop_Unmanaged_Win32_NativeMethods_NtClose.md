# NativeMethods.NtClose Method 
 

**Note: This API is now obsolete.**

Closes the specified object handle. 

 ( NtClose(IntPtr) function is superseded by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function. )

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", ExactSpelling = true)]
[ObsoleteAttribute("'NtClose' function is superseded by 'CloseHandle' function.")]
public static NTStatus NtClose(
	IntPtr hObject
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", ExactSpelling := true>]
<ObsoleteAttribute("'NtClose' function is superseded by 'CloseHandle' function.")>
Public Shared Function NtClose ( 
	hObject As IntPtr
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim hObject As IntPtr
Dim returnValue As NTStatus

returnValue = NativeMethods.NtClose(hObject)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", ExactSpelling = true)]
[ObsoleteAttribute(L"'NtClose' function is superseded by 'CloseHandle' function.")]
static NTStatus NtClose(
	[InAttribute] IntPtr hObject
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", ExactSpelling = true)>]
[<ObsoleteAttribute("'NtClose' function is superseded by 'CloseHandle' function.")>]
static member NtClose : 
        hObject : IntPtr -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>hObject</dt><dd>Type: System.IntPtr<br />The handle to the object being closed.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success, or the appropriate <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntclose" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winternl/nf-winternl-ntclose</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />