# NativeMethods.Wow64DisableWow64FsRedirection Method 
 

Disables file system redirection for the calling thread. 

 File system redirection is enabled by default.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool Wow64DisableWow64FsRedirection(
	out IntPtr refOldValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function Wow64DisableWow64FsRedirection ( 
	<OutAttribute> ByRef refOldValue As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refOldValue As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.Wow64DisableWow64FsRedirection(refOldValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool Wow64DisableWow64FsRedirection(
	[OutAttribute] IntPtr% refOldValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member Wow64DisableWow64FsRedirection : 
        refOldValue : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refOldValue</dt><dd>Type: System.IntPtr<br />The WOW64 file system redirection value. 

 The system uses this parameter to store information necessary to revert (re-enable) file system redirection. 

 Note: This value is for system use only. To avoid unpredictable behavior, do not modify this value in any way.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-wow64disablewow64fsredirection" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wow64apiset/nf-wow64apiset-wow64disablewow64fsredirection</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />