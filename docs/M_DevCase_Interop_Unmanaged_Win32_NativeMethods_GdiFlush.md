# NativeMethods.GdiFlush Method 
 

Flushes the calling thread's current batch.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", ExactSpelling = true, SetLastError = true)]
[SecurityCriticalAttribute]
public static bool GdiFlush()
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", ExactSpelling := true, SetLastError := true>]
<SecurityCriticalAttribute>
Public Shared Function GdiFlush As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.GdiFlush()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", ExactSpelling = true, SetLastError = true)]
[SecurityCriticalAttribute]
static bool GdiFlush()
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", ExactSpelling = true, SetLastError = true)>]
[<SecurityCriticalAttribute>]
static member GdiFlush : unit -> bool 

```


#### Return Value
Type: Boolean<br />If all functions in the current batch succeed, the return value is `true` (`True` in Visual Basic). 

 If not all functions in the current batch, the return value is `false` (`False` in Visual Basic), indicating that at least one function returned an error. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-gdiflush" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-gdiflush</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />