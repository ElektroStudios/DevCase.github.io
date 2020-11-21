# NativeMethods.EmptyWorkingSet Method 
 

Removes as many pages as possible from the working set of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", ExactSpelling = true, SetLastError = true)]
public static bool EmptyWorkingSet(
	IntPtr hProcess
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function EmptyWorkingSet ( 
	hProcess As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EmptyWorkingSet(hProcess)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", ExactSpelling = true, SetLastError = true)]
static bool EmptyWorkingSet(
	IntPtr hProcess
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", ExactSpelling = true, SetLastError = true)>]
static member EmptyWorkingSet : 
        hProcess : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">SetQuota</a> access right.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-emptyworkingset" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-emptyworkingset</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />