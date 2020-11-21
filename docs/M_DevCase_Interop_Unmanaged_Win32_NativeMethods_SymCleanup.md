# NativeMethods.SymCleanup Method 
 

Deallocates all resources associated with the process handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", SetLastError = true)]
public static bool SymCleanup(
	IntPtr hProcess
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", SetLastError := true>]
Public Shared Function SymCleanup ( 
	hProcess As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SymCleanup(hProcess)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", SetLastError = true)]
static bool SymCleanup(
	IntPtr hProcess
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", SetLastError = true)>]
static member SymCleanup : 
        hProcess : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process that was originally passed to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymInitialize">SymInitialize(IntPtr, String, Boolean)</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680696%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680696%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />