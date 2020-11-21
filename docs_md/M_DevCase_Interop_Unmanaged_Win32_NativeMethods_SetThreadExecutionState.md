# NativeMethods.SetThreadExecutionState Method 
 

Enables an application to inform the system that it is in use, thereby preventing the system from entering sleep or turning off the display while the application is running.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static ExecutionState SetThreadExecutionState(
	ExecutionState esFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetThreadExecutionState ( 
	esFlags As ExecutionState
) As ExecutionState
```

**VB Usage**<br />
``` VB Usage
Dim esFlags As ExecutionState
Dim returnValue As ExecutionState

returnValue = NativeMethods.SetThreadExecutionState(esFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static ExecutionState SetThreadExecutionState(
	ExecutionState esFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetThreadExecutionState : 
        esFlags : ExecutionState -> ExecutionState 

```


#### Parameters
&nbsp;<dl><dt>esFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExecutionState">DevCase.Interop.Unmanaged.Win32.Enums.ExecutionState</a><br />The thread's execution requirements. 

 This parameter can be one or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExecutionState">ExecutionState</a> values.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExecutionState">ExecutionState</a><br />If the function succeeds, the return value is the previous thread's <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExecutionState">ExecutionState</a> value. 

 If the function fails, the return value is a null reference (`Nothing` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa373208%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa373208%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />