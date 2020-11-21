# NativeMethods.GetTextMetricsW Method (IntPtr, TextMetricW)
 

Fills the specified buffer with the metrics for the currently selected font.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Unicode)]
public static bool GetTextMetricsW(
	IntPtr hdc,
	ref TextMetricW refMetrics
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Unicode>]
Public Shared Function GetTextMetricsW ( 
	hdc As IntPtr,
	ByRef refMetrics As TextMetricW
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim refMetrics As TextMetricW
Dim returnValue As Boolean

returnValue = NativeMethods.GetTextMetricsW(hdc, 
	refMetrics)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Unicode)]
static bool GetTextMetricsW(
	IntPtr hdc, 
	TextMetricW% refMetrics
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Unicode)>]
static member GetTextMetricsW : 
        hdc : IntPtr * 
        refMetrics : TextMetricW byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle To a DC (Device Context).</dd><dt>refMetrics</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricW">DevCase.Interop.Unmanaged.Win32.Structures.TextMetricW</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricW">TextMetricW</a> structure that receives the text metrics.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144941(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144941(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetTextMetricsW">GetTextMetricsW Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />