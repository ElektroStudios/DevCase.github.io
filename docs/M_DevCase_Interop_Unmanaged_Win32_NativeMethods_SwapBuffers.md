# NativeMethods.SwapBuffers Method 
 

Exchanges the front and back buffers if the current pixel format for the window referenced by the specified device context includes a back buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool SwapBuffers(
	IntPtr hDc
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function SwapBuffers ( 
	hDc As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SwapBuffers(hDc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool SwapBuffers(
	IntPtr hDc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member SwapBuffers : 
        hDc : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />Specifies a device context. 

 If the current pixel format for the window referenced by this device context includes a back buffer, the function exchanges the front and back buffers.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-swapbuffers" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-swapbuffers</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />