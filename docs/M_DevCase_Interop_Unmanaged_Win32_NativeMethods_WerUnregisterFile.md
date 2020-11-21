# NativeMethods.WerUnregisterFile Method 
 

Removes a file from the list of files to be added to reports generated for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult WerUnregisterFile(
	string filePath
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function WerUnregisterFile ( 
	filePath As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterFile(filePath)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult WerUnregisterFile(
	String^ filePath
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member WerUnregisterFile : 
        filePath : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The full path to the file. 

 This file must have been registered using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterFile">WerRegisterFile(String, WerRegisterFileType, WerRegisterFileTypeFlags)</a> function.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/werapi/nf-werapi-werunregisterfile" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/werapi/nf-werapi-werunregisterfile</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />