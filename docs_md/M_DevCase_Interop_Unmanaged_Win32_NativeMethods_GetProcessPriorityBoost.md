# NativeMethods.GetProcessPriorityBoost Method 
 

Retrieves the priority boost control state of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetProcessPriorityBoost(
	IntPtr hProcess,
	out bool refDisablePriorityBoost
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetProcessPriorityBoost ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refDisablePriorityBoost As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refDisablePriorityBoost As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.GetProcessPriorityBoost(hProcess, 
	refDisablePriorityBoost)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetProcessPriorityBoost(
	[InAttribute] IntPtr hProcess, 
	[OutAttribute] bool% refDisablePriorityBoost
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetProcessPriorityBoost : 
        hProcess : IntPtr * 
        refDisablePriorityBoost : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refDisablePriorityBoost</dt><dd>Type: System.Boolean<br />A pointer to a variable that receives the priority boost control state. 

 A value of `true` (`True` in Visual Basic) indicates that dynamic boosting is disabled. A value of `false` (`False` in Visual Basic) indicates normal behavior.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). In that case, the variable pointed to by the *refDisablePriorityBoost* parameter receives the priority boost control state. 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocesspriorityboost" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocesspriorityboost</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />