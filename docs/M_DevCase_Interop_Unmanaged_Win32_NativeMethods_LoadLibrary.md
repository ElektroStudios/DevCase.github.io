# NativeMethods.LoadLibrary Method 
 

Loads the specified module into the address space of the calling process. 

 The specified module may cause other modules to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static SafeModuleHandle LoadLibrary(
	string fileName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LoadLibrary ( 
	fileName As String
) As SafeModuleHandle
```

**VB Usage**<br />
``` VB Usage
Dim fileName As String
Dim returnValue As SafeModuleHandle

returnValue = NativeMethods.LoadLibrary(fileName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static SafeModuleHandle^ LoadLibrary(
	[InAttribute] String^ fileName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LoadLibrary : 
        fileName : string -> SafeModuleHandle 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />The name of the module. This can be either a library module (a .dll file) or an executable module (an .exe file). 

 The name specified is the file name of the module and is not related to the name stored in the library module itself, as specified by the LIBRARY keyword in the module-definition (.def) file. 

 If the string specifies a full path, the function searches only that path for the module. 

 If the string specifies a relative path or a module name without a path, the function uses a standard search strategy to find the module. 

 If the function cannot find the module, the function fails. When specifying a path, be sure to use backslashes (\), not forward slashes (/). 

 If the string specifies a module name without a path and the file name extension is omitted, the function appends the default library extension .dll to the module name. To prevent the function from appending .dll to the module name, include a trailing point character (.) in the module name string.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle">SafeModuleHandle</a><br />If the function succeeds, the return value is a handle to the module. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684175(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684175(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />