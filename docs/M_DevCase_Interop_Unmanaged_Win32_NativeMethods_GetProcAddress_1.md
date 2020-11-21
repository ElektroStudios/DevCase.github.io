# NativeMethods.GetProcAddress Method (IntPtr, String)
 

Retrieves the address of an exported function or variable from the specified dynamic-link library (DLL).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", BestFitMapping = false, ExactSpelling = true, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr GetProcAddress(
	IntPtr hModule,
	string procName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", BestFitMapping := false, ExactSpelling := true, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetProcAddress ( 
	hModule As IntPtr,
	procName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim procName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.GetProcAddress(hModule, 
	procName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", BestFitMapping = false, ExactSpelling = true, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr GetProcAddress(
	IntPtr hModule, 
	String^ procName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", BestFitMapping = false, ExactSpelling = true, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetProcAddress : 
        hModule : IntPtr * 
        procName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the DLL module that contains the function or variable. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandleEx">GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr)</a> function returns this handle. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcAddress">GetProcAddress(SafeModuleHandle, String)</a> function does not retrieve addresses from modules that were loaded using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadLibraryFlags">LoadLibraryAsDataFile</a> flag.</dd><dt>procName</dt><dd>Type: System.String<br />The function or variable name, or the function's ordinal value. 

 If this parameter is an ordinal value, it must be in the low-order word; the high-order word must be zero.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the address of the exported function or variable. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683212(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683212(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetProcAddress">GetProcAddress Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />