# NativeMethods.ApplicationRecoveryFinished Method 
 

Indicates that the calling application has completed its data recovery.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void ApplicationRecoveryFinished(
	bool success
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub ApplicationRecoveryFinished ( 
	success As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim success As BooleanNativeMethods.ApplicationRecoveryFinished(success)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void ApplicationRecoveryFinished(
	bool success
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member ApplicationRecoveryFinished : 
        success : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>success</dt><dd>Type: System.Boolean<br />Specify `true` (`True` in Visual Basic) to indicate that the data was successfully recovered; otherwise, `false` (`False` in Visual Basic).</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-applicationrecoveryfinished" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-applicationrecoveryfinished</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />