# NativeMethods.FatalExit Method 
 

Transfers execution control to the debugger. The behavior of the debugger thereafter is specific to the type of debugger used.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void FatalExit(
	int exitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub FatalExit ( 
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim exitCode As Integer

NativeMethods.FatalExit(exitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void FatalExit(
	int exitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member FatalExit : 
        exitCode : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>exitCode</dt><dd>Type: System.Int32<br />The error code associated with the exit.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-fatalexit" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-fatalexit</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />