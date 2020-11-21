# NativeMethods.AddDllDirectory Method 
 

Adds a directory to the process DLL search path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static IntPtr AddDllDirectory(
	string newDirectory
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function AddDllDirectory ( 
	newDirectory As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim newDirectory As String
Dim returnValue As IntPtr

returnValue = NativeMethods.AddDllDirectory(newDirectory)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static IntPtr AddDllDirectory(
	String^ newDirectory
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member AddDllDirectory : 
        newDirectory : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>newDirectory</dt><dd>Type: System.String<br />An absolute path to the directory to add to the search path. For example, to add the directory Dir2 to the process DLL search path, specify \Dir2.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is an opaque pointer that can be passed to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RemoveDllDirectory">RemoveDllDirectory(IntPtr)</a> to remove the DLL from the process DLL search path. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/sv-se/library/hh310513(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/sv-se/library/hh310513(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />