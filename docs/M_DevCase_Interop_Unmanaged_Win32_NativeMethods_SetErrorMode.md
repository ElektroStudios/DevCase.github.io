# NativeMethods.SetErrorMode Method 
 

Controls whether the system will handle the specified types of serious errors or whether the process will handle them for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ProcessErrorMode SetErrorMode(
	ProcessErrorMode newMode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function SetErrorMode ( 
	newMode As ProcessErrorMode
) As ProcessErrorMode
```

**VB Usage**<br />
``` VB Usage
Dim newMode As ProcessErrorMode
Dim returnValue As ProcessErrorMode

returnValue = NativeMethods.SetErrorMode(newMode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static ProcessErrorMode SetErrorMode(
	ProcessErrorMode newMode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member SetErrorMode : 
        newMode : ProcessErrorMode -> ProcessErrorMode 

```


#### Parameters
&nbsp;<dl><dt>newMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessErrorMode">DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode</a><br />The new process error mode.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessErrorMode">ProcessErrorMode</a><br />The previous process error mode.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680621(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680621(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />