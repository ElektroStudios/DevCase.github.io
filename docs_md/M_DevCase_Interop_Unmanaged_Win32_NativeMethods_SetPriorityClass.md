# NativeMethods.SetPriorityClass Method 
 

Sets the priority class for the specified process. 

 This value, together with the priority value of each thread of the process, determines each thread's base priority level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool SetPriorityClass(
	IntPtr hProcess,
	ProcessPriorityClass dwPriorityClass
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function SetPriorityClass ( 
	hProcess As IntPtr,
	dwPriorityClass As ProcessPriorityClass
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim dwPriorityClass As ProcessPriorityClass
Dim returnValue As Boolean

returnValue = NativeMethods.SetPriorityClass(hProcess, 
	dwPriorityClass)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool SetPriorityClass(
	IntPtr hProcess, 
	ProcessPriorityClass dwPriorityClass
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member SetPriorityClass : 
        hProcess : IntPtr * 
        dwPriorityClass : ProcessPriorityClass -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 This handle must be created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">SetInformation</a> access right.</dd><dt>dwPriorityClass</dt><dd>Type: System.Diagnostics.ProcessPriorityClass<br />The priority class for the process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms686219%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms686219%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />