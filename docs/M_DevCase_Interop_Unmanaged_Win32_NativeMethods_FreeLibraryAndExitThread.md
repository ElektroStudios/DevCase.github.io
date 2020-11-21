# NativeMethods.FreeLibraryAndExitThread Method 
 

Decrements the reference count of a loaded dynamic-link library (DLL) by one, then calls ExitThread to terminate the calling thread. 

 This function does not return a value. Invalid module handles are ignored.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void FreeLibraryAndExitThread(
	IntPtr hModule,
	uint exitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub FreeLibraryAndExitThread ( 
	hModule As IntPtr,
	exitCode As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim exitCode As UInteger

NativeMethods.FreeLibraryAndExitThread(hModule, 
	exitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void FreeLibraryAndExitThread(
	[InAttribute] IntPtr hModule, 
	unsigned int exitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member FreeLibraryAndExitThread : 
        hModule : IntPtr * 
        exitCode : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the DLL module whose reference count the function decrements. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandleEx">GetModuleHandleEx(GetModuleHandleExFlags, String, IntPtr)</a> function returns this handle. 

 Do not call this function with a handle returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleHandle">GetModuleHandle(String)</a> function, since this function does not maintain a reference count for the module.</dd><dt>exitCode</dt><dd>Type: System.UInt32<br />The exit code for the calling thread.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-freelibraryandexitthread" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-freelibraryandexitthread</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />