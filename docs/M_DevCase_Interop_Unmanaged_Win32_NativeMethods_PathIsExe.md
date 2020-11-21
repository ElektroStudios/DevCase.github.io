# NativeMethods.PathIsExe Method 
 

Determines whether a file is an executable by examining the file name extension.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static bool PathIsExe(
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Function PathIsExe ( 
	path As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsExe(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static bool PathIsExe(
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member PathIsExe : 
        path : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated, Unicode string that contains the file path, which includes the name of the file.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the file name extension is .cmd, .bat, .pif, .scf, .exe, .com, or .scr; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathisexe" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathisexe</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />