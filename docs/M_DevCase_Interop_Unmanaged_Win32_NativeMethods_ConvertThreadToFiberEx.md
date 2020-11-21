# NativeMethods.ConvertThreadToFiberEx Method 
 

Converts the current thread into a fiber. 

 You must convert a thread into a fiber before you can schedule other fibers.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr ConvertThreadToFiberEx(
	IntPtr parameter,
	FiberFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ConvertThreadToFiberEx ( 
	parameter As IntPtr,
	flags As FiberFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim parameter As IntPtr
Dim flags As FiberFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.ConvertThreadToFiberEx(parameter, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr ConvertThreadToFiberEx(
	IntPtr parameter, 
	FiberFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ConvertThreadToFiberEx : 
        parameter : IntPtr * 
        flags : FiberFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>parameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable that is passed to the fiber. The fiber can retrieve this data by using the GetFiberData macro.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FiberFlags">DevCase.Interop.Unmanaged.Win32.Enums.FiberFlags</a><br />If this parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FiberFlags">None</a>, the floating-point state on x86 systems is not switched and data can be corrupted if a fiber uses floating-point arithmetic. 

 If this parameter is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FiberFlags">FloatSwitch</a>, the floating-point state is switched for the fiber.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the address of the fiber. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-convertthreadtofiberex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-convertthreadtofiberex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />