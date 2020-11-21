# NativeMethods.GetSystemMetricsForDpi Method 
 

Retrieves the specified system metric or system configuration setting taking into account a provided DPI.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetSystemMetricsForDpi(
	int index,
	uint dpi
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetSystemMetricsForDpi ( 
	index As Integer,
	dpi As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim index As Integer
Dim dpi As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetSystemMetricsForDpi(index, 
	dpi)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetSystemMetricsForDpi(
	int index, 
	unsigned int dpi
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetSystemMetricsForDpi : 
        index : int * 
        dpi : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The system metric or configuration setting to be retrieved.</dd><dt>dpi</dt><dd>Type: System.UInt32<br />The DPI to use for scaling the metric.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getsystemmetricsfordpi" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getsystemmetricsfordpi</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />