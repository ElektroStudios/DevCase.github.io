# NativeMethods.SignalFileOpen Method (PIDL)
 

Sends a notification to the Shell that the specified file has been opened.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SignalFileOpen(
	PIDL pidl
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SignalFileOpen ( 
	pidl As PIDL
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pidl As PIDL
Dim returnValue As Boolean

returnValue = NativeMethods.SignalFileOpen(pidl)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
static bool SignalFileOpen(
	PIDL^ pidl
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
static member SignalFileOpen : 
        pidl : PIDL -> bool 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> that specifies the file.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful; otherwise `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-signalfileopen" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-signalfileopen</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SignalFileOpen">SignalFileOpen Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />