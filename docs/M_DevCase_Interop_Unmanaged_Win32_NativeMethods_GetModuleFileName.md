# NativeMethods.GetModuleFileName Method 
 

Retrieves the fully qualified path for the file that contains the specified module. The module must have been loaded by the current process. 

 To locate the file for a module that was loaded by another process, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetModuleFileNameEx">GetModuleFileNameEx(IntPtr, IntPtr, StringBuilder, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetModuleFileName(
	IntPtr hModule,
	StringBuilder filename,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetModuleFileName ( 
	hModule As IntPtr,
	filename As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hModule As IntPtr
Dim filename As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetModuleFileName(hModule, 
	filename, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetModuleFileName(
	IntPtr hModule, 
	StringBuilder^ filename, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetModuleFileName : 
        hModule : IntPtr * 
        filename : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the loaded module whose path is being requested. 

 If this parameter is a null reference (`Nothing` in Visual Basic), GetModuleFileName(IntPtr, StringBuilder, UInt32) retrieves the path of the executable file of the current process. 

 The GetModuleFileName(IntPtr, StringBuilder, UInt32) function does not retrieve the path for modules that were loaded using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadLibraryFlags">LoadLibraryAsDataFile</a> flag.</dd><dt>filename</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the fully qualified path of the module. 

 If the length of the path is less than the size that the *size* parameter specifies, the function succeeds and the path is returned as a null-terminated string.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the *filename* buffer.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string that is copied to the buffer, in characters, not including the terminating null character. 

 If the buffer is too small to hold the module name, the string is truncated to *size* characters including the terminating null character, the function returns *size*, and the function sets the last error to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INSUFFICIENT_BUFFER</a>. 

 If *size* is zero, the return value is 0 (zero) and the last error code is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>. 

 If the function fails, the return value is 0 (zero). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-getmodulefilenamea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/libloaderapi/nf-libloaderapi-getmodulefilenamea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />