# NativeMethods.OutputDebugString Method 
 

Sends a string to the debugger for display.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static void OutputDebugString(
	string outputString
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Sub OutputDebugString ( 
	outputString As String
)
```

**VB Usage**<br />
``` VB Usage
Dim outputString As StringNativeMethods.OutputDebugString(outputString)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static void OutputDebugString(
	String^ outputString
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member OutputDebugString : 
        outputString : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>outputString</dt><dd>Type: System.String<br />The null-terminated string to be displayed.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa363362(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa363362(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />