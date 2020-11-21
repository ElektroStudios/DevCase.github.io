# NativeMethods.ConvertThreadToFiber Method 
 

Converts the current thread into a fiber. 

 You must convert a thread into a fiber before you can schedule other fibers.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr ConvertThreadToFiber(
	IntPtr parameter
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function ConvertThreadToFiber ( 
	parameter As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim parameter As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.ConvertThreadToFiber(parameter)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr ConvertThreadToFiber(
	[InAttribute] IntPtr parameter
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ConvertThreadToFiber : 
        parameter : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>parameter</dt><dd>Type: System.IntPtr<br />A pointer to a variable that is passed to the fiber. 

 The fiber can retrieve this data by using the `GetFiberData` macro.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the address of the fiber. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-convertthreadtofiber" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-convertthreadtofiber</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />