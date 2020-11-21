# NativeMethods.SymLoadModuleEx Method 
 

Loads the symbol table for the specified module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static ulong SymLoadModuleEx(
	IntPtr hProcess,
	IntPtr hFile,
	string imageName,
	string moduleName,
	ulong baseOfDll,
	int dllSize,
	IntPtr data,
	SymLoadModuleFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SymLoadModuleEx ( 
	hProcess As IntPtr,
	hFile As IntPtr,
	imageName As String,
	moduleName As String,
	baseOfDll As ULong,
	dllSize As Integer,
	data As IntPtr,
	flags As SymLoadModuleFlags
) As ULong
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim hFile As IntPtr
Dim imageName As String
Dim moduleName As String
Dim baseOfDll As ULong
Dim dllSize As Integer
Dim data As IntPtr
Dim flags As SymLoadModuleFlags
Dim returnValue As ULong

returnValue = NativeMethods.SymLoadModuleEx(hProcess, 
	hFile, imageName, moduleName, baseOfDll, 
	dllSize, data, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned long long SymLoadModuleEx(
	IntPtr hProcess, 
	IntPtr hFile, 
	String^ imageName, 
	String^ moduleName, 
	unsigned long long baseOfDll, 
	int dllSize, 
	IntPtr data, 
	SymLoadModuleFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SymLoadModuleEx : 
        hProcess : IntPtr * 
        hFile : IntPtr * 
        imageName : string * 
        moduleName : string * 
        baseOfDll : uint64 * 
        dllSize : int * 
        data : IntPtr * 
        flags : SymLoadModuleFlags -> uint64 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process that was originally passed to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymInitialize">SymInitialize(IntPtr, String, Boolean)</a> function.</dd><dt>hFile</dt><dd>Type: System.IntPtr<br />The `h fileA` handle to the file for the executable image. 

 This argument is used mostly by debuggers, where the debugger passes the file handle obtained from a debugging event. 

 A value of Zero indicates that *hFile* is not used.</dd><dt>imageName</dt><dd>Type: System.String<br />The name of the executable image. 

 This name can contain a partial path, a full path, or no path at all. 

 If the file cannot be located by the name provided, the symbol search path is used.</dd><dt>moduleName</dt><dd>Type: System.String<br />A shortcut name for the module. 

 If the pointer value is a null reference (`Nothing` in Visual Basic), the library creates a name using the base name of the symbol file.</dd><dt>baseOfDll</dt><dd>Type: System.UInt64<br />The load address of the module. 

 If the value is zero, the library obtains the load address from the symbol file. 

 The load address contained in the symbol file is not necessarily the actual load address. 

 Debuggers and other applications having an actual load address should use the real load address when calling this function. 

 If the image is a `.pdb` file, this parameter cannot be zero.</dd><dt>dllSize</dt><dd>Type: System.Int32<br />The size of the module, in bytes. 

 If the value is zero, the library obtains the size from the symbol file. 

 The size contained in the symbol file is not necessarily the actual size. 

 Debuggers and other applications having an actual size should use the real size when calling this function. 

 If the image is a `.pdb` file, this parameter cannot be zero.</dd><dt>data</dt><dd>Type: System.IntPtr<br />A pointer to a `MODLOAD_DATA` structure that represents headers other than the standard PE header. 

 This parameter is optional and can be Zero.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymLoadModuleFlags">DevCase.Interop.Unmanaged.Win32.Enums.SymLoadModuleFlags</a><br />This parameter can be one or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymLoadModuleFlags">SymLoadModuleFlags</a> Enum values.</dd></dl>

#### Return Value
Type: UInt64<br />If the function succeeds, the return value is the base address of the loaded module. 

 If the function fails, the return value is zero. 

 To retrieve extended error information, call GetLastWin32Error(). 

 If the module is already loaded, the return value is zero and GetLastWin32Error() returns `ERROR_SUCCESS`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681353%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681353%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />