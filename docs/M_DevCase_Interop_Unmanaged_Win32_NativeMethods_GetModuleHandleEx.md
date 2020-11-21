# NativeMethods.GetModuleHandleEx Method 
 

Retrieves a module handle for the specified module and increments the module's reference count unless <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetModuleHandleExFlags">UnchangedReferenceCount</a> flag is specified. 

 The module must have been loaded by the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetModuleHandleEx(
	GetModuleHandleExFlags flags,
	[OptionalAttribute] string moduleName,
	out IntPtr refModule
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetModuleHandleEx ( 
	flags As GetModuleHandleExFlags,
	<OptionalAttribute> moduleName As String,
	<OutAttribute> ByRef refModule As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim flags As GetModuleHandleExFlags
Dim moduleName As String
Dim refModule As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.GetModuleHandleEx(flags, 
	moduleName, refModule)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetModuleHandleEx(
	GetModuleHandleExFlags flags, 
	[OptionalAttribute] String^ moduleName, 
	[OutAttribute] IntPtr% refModule
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetModuleHandleEx : 
        flags : GetModuleHandleExFlags * 
        [<OptionalAttribute>] moduleName : string * 
        refModule : IntPtr byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetModuleHandleExFlags">DevCase.Interop.Unmanaged.Win32.Enums.GetModuleHandleExFlags</a><br />Flags that determines the load behavior. 

 If the module's reference count is incremented, the caller must use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeLibrary">FreeLibrary(SafeModuleHandle)</a> function to decrement the reference count when the module handle is no longer needed.</dd><dt>moduleName (Optional)</dt><dd>Type: System.String<br />The name Of the loaded Module (either a .dll Or .exe file), Or an address In the Module (If *flags* Is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetModuleHandleExFlags">FromAddress</a>). 

 For a module name, if the file name extension Is omitted, the default library extension .dll Is appended. 

 The file name string can include a trailing point character (.) To indicate that the Module name has no extension. 

 The String does Not have To specify a path. When specifying a path, be sure To use backslashes (\), Not forward slashes (/). 

 The name Is compared (Case independently) To the names Of modules currently mapped into the address space Of the calling process. 

 If this parameter Is a null reference (`Nothing` in Visual Basic), the Function returns a handle To the file used To create the calling process (.exe file).</dd><dt>refModule</dt><dd>Type: System.IntPtr<br />A handle to the specified module. If the function fails, this parameter is Zero. 

 The GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr) function does not retrieve handles for modules that were loaded using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadLibraryFlags">LoadLibraryAsDataFile</a> flag.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms683200(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms683200(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />