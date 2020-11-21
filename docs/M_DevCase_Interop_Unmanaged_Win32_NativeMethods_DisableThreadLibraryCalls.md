# NativeMethods.DisableThreadLibraryCalls Method 
 

Disables the DLL_THREAD_ATTACH and DLL_THREAD_DETACH notifications for the specified dynamic-link library (DLL). This can reduce the size of the working set for some applications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool DisableThreadLibraryCalls(
	IntPtr hModule
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function DisableThreadLibraryCalls ( 
	hModule As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DisableThreadLibraryCalls(hModule)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool DisableThreadLibraryCalls(
	[InAttribute] IntPtr hModule
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member DisableThreadLibraryCalls : 
        hModule : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the DLL module for which the DLL_THREAD_ATTACH and DLL_THREAD_DETACH notifications are to be disabled. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a>, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a>, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a> function returns this handle. 

 Note that you cannot call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a> with a null reference (`Nothing` in Visual Basic) because this returns the base address of the executable image, not the DLL image. 

 The DisableThreadLibraryCalls(IntPtr) function fails if the DLL specified by *hModule* has active static thread local storage, or if *hModule* is an invalid module handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-disablethreadlibrarycalls" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-disablethreadlibrarycalls</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />