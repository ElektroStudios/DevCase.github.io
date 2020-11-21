# NativeMethods.Wow64EnableWow64FsRedirection Method 
 

Enables or disables file system redirection for the calling thread. 

 This function may not work reliably when there are nested calls. Therefore, this function has been replaced by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64DisableWow64FsRedirection">Wow64DisableWow64FsRedirection(IntPtr)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64RevertWow64FsRedirection">Wow64RevertWow64FsRedirection(IntPtr)</a> functions. 

 Note: These two methods of controlling file system redirection cannot be combined in any way. Do not use the Wow64EnableWow64FsRedirection(Boolean) function with either the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64DisableWow64FsRedirection">Wow64DisableWow64FsRedirection(IntPtr)</a> or the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64RevertWow64FsRedirection">Wow64RevertWow64FsRedirection(IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool Wow64EnableWow64FsRedirection(
	bool enable
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function Wow64EnableWow64FsRedirection ( 
	enable As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim enable As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.Wow64EnableWow64FsRedirection(enable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool Wow64EnableWow64FsRedirection(
	bool enable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member Wow64EnableWow64FsRedirection : 
        enable : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>enable</dt><dd>Type: System.Boolean<br />Indicates the type of request for WOW64 system folder redirection. 

 If `true` (`True` in Visual Basic), requests redirection be enabled; if `false` (`False` in Visual Basic), requests redirection be disabled.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeded; `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-wow64enablewow64fsredirection" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-wow64enablewow64fsredirection</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />