# NativeMethods.DwmIsCompositionEnabled Method 
 

Obtains a value that indicates whether Desktop Window Manager (DWM) composition is enabled. 

 Applications on machines running Windows 7 or earlier can listen for composition state changes by handling the `WM_DWMCOMPOSITIONCHANGED` notification.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmIsCompositionEnabled(
	ref bool refEnabled
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmIsCompositionEnabled ( 
	ByRef refEnabled As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim refEnabled As Boolean
Dim returnValue As Integer

returnValue = NativeMethods.DwmIsCompositionEnabled(refEnabled)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmIsCompositionEnabled(
	bool% refEnabled
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmIsCompositionEnabled : 
        refEnabled : bool byref -> int 

```


#### Parameters
&nbsp;<dl><dt>refEnabled</dt><dd>Type: System.Boolean<br />A pointer to a value that, when this function returns successfully, receives `true` (`True` in Visual Basic) if DWM composition is enabled; otherwise, `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa969518%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa969518%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />