# NativeMethods.LoadLibraryEx Method 
 

Loads the specified module into the address space of the calling process. 

 The specified module may cause other modules to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static SafeModuleHandle LoadLibraryEx(
	string fileName,
	[OptionalAttribute] IntPtr hFile,
	LoadLibraryFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LoadLibraryEx ( 
	fileName As String,
	<OptionalAttribute> hFile As IntPtr,
	flags As LoadLibraryFlags
) As SafeModuleHandle
```

**VB Usage**<br />
``` VB Usage
Dim fileName As String
Dim hFile As IntPtr
Dim flags As LoadLibraryFlags
Dim returnValue As SafeModuleHandle

returnValue = NativeMethods.LoadLibraryEx(fileName, 
	hFile, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static SafeModuleHandle^ LoadLibraryEx(
	String^ fileName, 
	[OptionalAttribute] IntPtr hFile, 
	LoadLibraryFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LoadLibraryEx : 
        fileName : string * 
        [<OptionalAttribute>] hFile : IntPtr * 
        flags : LoadLibraryFlags -> SafeModuleHandle 

```


#### Parameters
&nbsp;<dl><dt>fileName</dt><dd>Type: System.String<br />A string that specifies the file name of the module to load. 

 This name is not related to the name stored in a library module itself, as specified by the LIBRARY keyword in the module-definition (.def) file. 

 The module can be a library module (a .dll file) or an executable module (an .exe file). If the specified module is an executable module, static imports are not loaded; instead, the module is loaded as if <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadLibraryFlags">DontResolveDllReferences</a> was specified. 

 If the string specifies a module name without a path and the file name extension is omitted, the function appends the default library extension .dll to the module name. To prevent the function from appending .dll to the module name, include a trailing point character (.) in the module name string. 

 If the string specifies a fully qualified path, the function searches only that path for the module. When specifying a path, be sure to use backslashes (\), not forward slashes (/). 

 If the string specifies a module name without a path and more than one loaded module has the same base name and extension, the function returns a handle to the module that was loaded first. 

 If the string specifies a module name without a path and a module of the same name is not already loaded, or if the string specifies a module name with a relative path, the function searches for the specified module. The function also searches for modules if loading the specified module causes the system to load other associated modules (that is, if the module has dependencies). The directories that are searched and the order in which they are searched depend on the specified path and the *flags* parameter. 

 If the function cannot find the module or one of its dependencies, the function fails.</dd><dt>hFile (Optional)</dt><dd>Type: System.IntPtr<br />This parameter is reserved for future use. It must be NULL.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadLibraryFlags">DevCase.Interop.Unmanaged.Win32.Enums.LoadLibraryFlags</a><br />The action to be taken when loading the module. 

 If no flags are specified, the behavior of this function is identical to that of the LoadLibrary function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle">SafeModuleHandle</a><br />If the function succeeds, the return value is a handle to the loaded module. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684179(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684179(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />