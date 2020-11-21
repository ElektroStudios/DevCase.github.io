# NativeMethods.GetTextMetricsA Method (HandleRef, TextMetricA)
 

Fills the specified buffer with the metrics for the currently selected font.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Ansi)]
public static bool GetTextMetricsA(
	HandleRef hdc,
	ref TextMetricA refMetrics
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Ansi>]
Public Shared Function GetTextMetricsA ( 
	hdc As HandleRef,
	ByRef refMetrics As TextMetricA
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As HandleRef
Dim refMetrics As TextMetricA
Dim returnValue As Boolean

returnValue = NativeMethods.GetTextMetricsA(hdc, 
	refMetrics)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Ansi)]
static bool GetTextMetricsA(
	HandleRef hdc, 
	TextMetricA% refMetrics
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Ansi)>]
static member GetTextMetricsA : 
        hdc : HandleRef * 
        refMetrics : TextMetricA byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.HandleRef<br />A handle To a DC (Device Context).</dd><dt>refMetrics</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA">DevCase.Interop.Unmanaged.Win32.Structures.TextMetricA</a><br />A pointer to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA">TextMetricA</a> structure that receives the text metrics.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144941(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144941(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetTextMetricsA">GetTextMetricsA Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />