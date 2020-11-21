# NativeMethods.GetCommandLine Method 
 

Retrieves the command-line string for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto)]
public static string GetCommandLine()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto>]
Public Shared Function GetCommandLine As String
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As String

returnValue = NativeMethods.GetCommandLine()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto)]
static String^ GetCommandLine()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto)>]
static member GetCommandLine : unit -> string 

```


#### Return Value
Type: String<br />The command-line string for the current process.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683156(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683156(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />