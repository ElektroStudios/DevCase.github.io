# NativeMethods.RemoveDllDirectory Method 
 

Removes a directory that was added to the process DLL search path by using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AddDllDirectory">AddDllDirectory(String)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool RemoveDllDirectory(
	IntPtr cookie
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function RemoveDllDirectory ( 
	cookie As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim cookie As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.RemoveDllDirectory(cookie)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool RemoveDllDirectory(
	IntPtr cookie
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member RemoveDllDirectory : 
        cookie : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>cookie</dt><dd>Type: System.IntPtr<br />The cookie returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_AddDllDirectory">AddDllDirectory(String)</a> when the directory was added to the search path.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/sv-se/library/hh310514(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/sv-se/library/hh310514(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />