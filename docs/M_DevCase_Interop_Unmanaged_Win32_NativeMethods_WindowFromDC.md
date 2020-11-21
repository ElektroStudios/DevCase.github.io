# NativeMethods.WindowFromDC Method 
 

Returns a handle to the window associated with the specified display device context (DC). 

 Output functions that use the specified device context draw into this window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr WindowFromDC(
	IntPtr hDC
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function WindowFromDC ( 
	hDC As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hDC As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.WindowFromDC(hDC)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr WindowFromDC(
	IntPtr hDC
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member WindowFromDC : 
        hDC : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hDC</dt><dd>Type: System.IntPtr<br />Handle to the device context from which a handle to the associated window is to be retrieved.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is a handle to the window associated with the specified DC. 

 If no window is associated with the specified DC, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-windowfromdc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-windowfromdc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />