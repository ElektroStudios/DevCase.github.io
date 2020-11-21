# NativeMethods.DebugBreak Method 
 

Causes a breakpoint exception to occur in the current process. This allows the calling thread to signal the debugger to handle the exception. 

 To cause a breakpoint exception in another process, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DebugBreakProcess">DebugBreakProcess(IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void DebugBreak()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub DebugBreak
```

**VB Usage**<br />
``` VB Usage

NativeMethods.DebugBreak()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void DebugBreak()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member DebugBreak : unit -> unit 

```


## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679297(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679297(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />