# NativeMethods.Wow64RevertWow64FsRedirection Method 
 

Restores file system redirection for the calling thread. 

 This function should not be called without a previous call to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64DisableWow64FsRedirection">Wow64DisableWow64FsRedirection(IntPtr)</a>. 

 Any data allocation on behalf of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_Wow64DisableWow64FsRedirection">Wow64DisableWow64FsRedirection(IntPtr)</a> function is cleaned up by this function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool Wow64RevertWow64FsRedirection(
	IntPtr oldValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function Wow64RevertWow64FsRedirection ( 
	oldValue As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim oldValue As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.Wow64RevertWow64FsRedirection(oldValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool Wow64RevertWow64FsRedirection(
	IntPtr oldValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member Wow64RevertWow64FsRedirection : 
        oldValue : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>oldValue</dt><dd>Type: System.IntPtr<br />TBD</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-wow64revertwow64fsredirection" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-wow64revertwow64fsredirection</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />