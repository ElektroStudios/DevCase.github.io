# NativeMethods.GetModuleFileNameEx Method 
 

Retrieves the fully qualified path for the file containing the specified module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GetModuleFileNameEx(
	IntPtr hProcess,
	IntPtr hModule,
	StringBuilder filename,
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("PsApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetModuleFileNameEx ( 
	hProcess As IntPtr,
	hModule As IntPtr,
	filename As StringBuilder,
	size As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim hModule As IntPtr
Dim filename As StringBuilder
Dim size As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetModuleFileNameEx(hProcess, 
	hModule, filename, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PsApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GetModuleFileNameEx(
	IntPtr hProcess, 
	IntPtr hModule, 
	StringBuilder^ filename, 
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PsApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetModuleFileNameEx : 
        hProcess : IntPtr * 
        hModule : IntPtr * 
        filename : StringBuilder * 
        size : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process that contains the module. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> access rights.</dd><dt>hModule</dt><dd>Type: System.IntPtr<br />A handle to the module. 

 If this parameter is a null reference (`Nothing` in Visual Basic), GetModuleFileNameEx(IntPtr, IntPtr, StringBuilder, UInt32) retrieves the path of the executable file of the process specified in *hProcess*.</dd><dt>filename</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that receives the fully qualified path to the module. 

 If the size of the file name is larger than the value of the *size* parameter, the function succeeds but the file name is truncated and null-terminated.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size of the *filename* buffer.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string that is copied to the buffer, in characters, not including the terminating null character. 

 If the function fails, the return value is 0 (zero). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmodulefilenameexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/psapi/nf-psapi-getmodulefilenameexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />