# NativeMethods.FreeLibrary Method (SafeModuleHandle)
 

Frees the loaded dynamic-link library (DLL) module and, if necessary, decrements its reference count. 

 When the reference count reaches zero, the module is unloaded from the address space of the calling process and the handle is no longer valid.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool FreeLibrary(
	SafeModuleHandle handle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function FreeLibrary ( 
	handle As SafeModuleHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim handle As SafeModuleHandle
Dim returnValue As Boolean

returnValue = NativeMethods.FreeLibrary(handle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool FreeLibrary(
	SafeModuleHandle^ handle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member FreeLibrary : 
        handle : SafeModuleHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>handle</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeModuleHandle</a><br />A handle to the loaded library module. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandleEx">GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr)</a> function returns this handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683152(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683152(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_FreeLibrary">FreeLibrary Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />