# NativeMethods.SwitchToFiber Method 
 

Schedules a fiber. 

 This function must be called on a fiber.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static void SwitchToFiber(
	IntPtr fiber
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Sub SwitchToFiber ( 
	fiber As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim fiber As IntPtrNativeMethods.SwitchToFiber(fiber)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static void SwitchToFiber(
	[InAttribute] IntPtr fiber
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SwitchToFiber : 
        fiber : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>fiber</dt><dd>Type: System.IntPtr<br />The address of the fiber to be scheduled.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-switchtofiber" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-switchtofiber</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />