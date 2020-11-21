# NativeMethods.SymInitialize Method 
 

Initializes the symbol handler for a process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SymInitialize(
	IntPtr hProcess,
	string userSearchPath,
	bool fInvadeProcess
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SymInitialize ( 
	hProcess As IntPtr,
	userSearchPath As String,
	fInvadeProcess As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim userSearchPath As String
Dim fInvadeProcess As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SymInitialize(hProcess, 
	userSearchPath, fInvadeProcess)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SymInitialize(
	IntPtr hProcess, 
	String^ userSearchPath, 
	bool fInvadeProcess
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SymInitialize : 
        hProcess : IntPtr * 
        userSearchPath : string * 
        fInvadeProcess : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle that identifies the caller. 

 This value should be unique and nonzero, but need not be a process handle, However, if you do use a process handle, be sure to use the correct handle. 

 If the application is a debugger, use the process handle for the process being debugged. 

 Do not use the handle returned by `GetCurrentProcess` when debugging another process, because calling functions like <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymLoadModuleEx">SymLoadModuleEx(IntPtr, IntPtr, String, String, UInt64, Int32, IntPtr, SymLoadModuleFlags)</a> can have unexpected results.</dd><dt>userSearchPath</dt><dd>Type: System.String<br />The path, or series of paths separated by a semicolon (;), that is used to search for symbol files. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the library attempts to form a symbol path from the following sources: 

 The current working directory of the application. 

 The `_NT_SYMBOL_PATH` environment variable. 

 The `_NT_ALTERNATE_SYMBOL_PATH` environment variable.</dd><dt>fInvadeProcess</dt><dd>Type: System.Boolean<br />If this value is `true` (`True` in Visual Basic), enumerates the loaded modules for the process and effectively calls the `SymLoadModule64` function for each module.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681351%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681351%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />