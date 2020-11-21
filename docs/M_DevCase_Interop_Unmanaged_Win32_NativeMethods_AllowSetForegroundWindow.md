# NativeMethods.AllowSetForegroundWindow Method 
 

Enables the specified process to set the foreground window using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetForegroundWindow">SetForegroundWindow(IntPtr)</a> function. 

 The calling process must already be able to set the foreground window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool AllowSetForegroundWindow(
	int processId
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function AllowSetForegroundWindow ( 
	processId As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processId As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.AllowSetForegroundWindow(processId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool AllowSetForegroundWindow(
	int processId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member AllowSetForegroundWindow : 
        processId : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.Int32<br />The identifier of the process that will be enabled to set the foreground window. 

 If this parameter is `ASFW_ANY` (`-1`), all processes will be enabled to set the foreground window</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms632668(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms632668(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />