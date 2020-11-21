# NativeMethods.GetErrorMode Method 
 

Retrieves the error mode for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static ProcessErrorMode GetErrorMode()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function GetErrorMode As ProcessErrorMode
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As ProcessErrorMode

returnValue = NativeMethods.GetErrorMode()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static ProcessErrorMode GetErrorMode()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member GetErrorMode : unit -> ProcessErrorMode 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessErrorMode">ProcessErrorMode</a><br />The process error mode.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679355(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679355(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />