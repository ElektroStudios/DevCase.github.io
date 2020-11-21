# NativeMethods.DbgBreakPoint Method 
 

Breaks into the kernel debugger.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", ExactSpelling = true)]
public static void DbgBreakPoint()
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", ExactSpelling := true>]
Public Shared Sub DbgBreakPoint
```

**VB Usage**<br />
``` VB Usage

NativeMethods.DbgBreakPoint()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", ExactSpelling = true)]
static void DbgBreakPoint()
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", ExactSpelling = true)>]
static member DbgBreakPoint : unit -> unit 

```


## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-dbgbreakpoint" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-dbgbreakpoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />