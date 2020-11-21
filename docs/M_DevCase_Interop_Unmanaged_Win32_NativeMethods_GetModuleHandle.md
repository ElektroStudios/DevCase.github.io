# NativeMethods.GetModuleHandle Method 
 

Retrieves a module handle for the specified module. 

 The module must have been loaded by the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr GetModuleHandle(
	[OptionalAttribute] string moduleName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetModuleHandle ( 
	<OptionalAttribute> moduleName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim moduleName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.GetModuleHandle(moduleName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr GetModuleHandle(
	[OptionalAttribute] String^ moduleName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetModuleHandle : 
        [<OptionalAttribute>] moduleName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>moduleName (Optional)</dt><dd>Type: System.String<br />The name of the loaded module (either a .dll or .exe file). 

 If the file name extension is omitted, the default library extension .dll is appended. 

 The file name string can include a trailing point character (`.`) to indicate that the module name has no extension. The string does not have to specify a path. 

 When specifying a path, be sure to use backslashes (`\`), not forward slashes (`/`). 

 The name is compared (case independently) to the names of modules currently mapped into the address space of the calling process. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the function returns a handle to the file used to create the calling process (`.exe` file).</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the specified module. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683199%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683199%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />