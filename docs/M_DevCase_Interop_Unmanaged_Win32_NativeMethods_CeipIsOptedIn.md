# NativeMethods.CeipIsOptedIn Method 
 

Checks whether the user has opted in for SQM data collection as part of the Customer Experience Improvement Program (CEIP).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool CeipIsOptedIn()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function CeipIsOptedIn As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.CeipIsOptedIn()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool CeipIsOptedIn()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member CeipIsOptedIn : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if SQM data collection is opted in and the machine can send data. Otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/windowsceip/nf-windowsceip-ceipisoptedin" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/windowsceip/nf-windowsceip-ceipisoptedin</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />