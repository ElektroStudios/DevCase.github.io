# NativeMethods.SetProcessPriorityBoost Method 
 

Disables or enables the ability of the system to temporarily boost the priority of the threads of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetProcessPriorityBoost(
	IntPtr hProcess,
	bool disablePriorityBoost
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetProcessPriorityBoost ( 
	hProcess As IntPtr,
	disablePriorityBoost As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim disablePriorityBoost As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessPriorityBoost(hProcess, 
	disablePriorityBoost)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetProcessPriorityBoost(
	[InAttribute] IntPtr hProcess, 
	bool disablePriorityBoost
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetProcessPriorityBoost : 
        hProcess : IntPtr * 
        disablePriorityBoost : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. This handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">SetInformation</a> access right.</dd><dt>disablePriorityBoost</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), dynamic boosting is disabled. If the parameter is `false` (`False` in Visual Basic), dynamic boosting is enabled.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setprocesspriorityboost" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setprocesspriorityboost</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />