# NativeMethods.IsThreadAFiber Method 
 

Determines whether the current thread is a fiber.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool IsThreadAFiber()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function IsThreadAFiber As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.IsThreadAFiber()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool IsThreadAFiber()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member IsThreadAFiber : unit -> bool 

```


#### Return Value
Type: Boolean<br />The function returns `true` (`True` in Visual Basic) if the thread is a fiber and `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fibersapi/nf-fibersapi-isthreadafiber" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fibersapi/nf-fibersapi-isthreadafiber</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />