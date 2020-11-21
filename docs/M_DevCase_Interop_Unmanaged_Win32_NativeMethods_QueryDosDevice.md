# NativeMethods.QueryDosDevice Method (String, IntPtr, UInt32)
 

Retrieves information about MS-DOS device names. 

 The function can obtain the current mapping for a particular MS-DOS device name. The function can also obtain a list of all existing MS-DOS device names. 

 MS-DOS device names are stored as junctions in the object namespace. The code that converts an MS-DOS path into a corresponding path uses these junctions to map MS-DOS devices and drive letters. 

 The QueryDosDevice(String, IntPtr, UInt32) function enables an application to query the names of the junctions used to implement the MS-DOS device Namespace DevCase.Interop.as well as the value of each specific junction.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint QueryDosDevice(
	string deviceName,
	IntPtr targetPath,
	uint maxChars
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function QueryDosDevice ( 
	deviceName As String,
	targetPath As IntPtr,
	maxChars As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim deviceName As String
Dim targetPath As IntPtr
Dim maxChars As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.QueryDosDevice(deviceName, 
	targetPath, maxChars)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int QueryDosDevice(
	String^ deviceName, 
	IntPtr targetPath, 
	unsigned int maxChars
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member QueryDosDevice : 
        deviceName : string * 
        targetPath : IntPtr * 
        maxChars : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>deviceName</dt><dd>Type: System.String<br />An MS-DOS device name string specifying the target of the query. 

 The device name cannot have a trailing backslash; for example, use "C:", not "C:\". 

 This parameter can be a null reference (`Nothing` in Visual Basic). In that case, the function will store a list of all existing MS-DOS device names into the buffer pointed to by *targetPath*.</dd><dt>targetPath</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that will receive the result of the query. 

 The function fills this buffer with one or more null-terminated strings. 

 The final null-terminated string is followed by an additional NULL. 

 If *deviceName* is non-a null reference (`Nothing` in Visual Basic), the function retrieves information about the particular MS-DOS device specified by *deviceName*. The first null-terminated string stored into the buffer is the current mapping for the device. The other null-terminated strings represent undeleted prior mappings for the device. 

 If *deviceName* is a null reference (`Nothing` in Visual Basic), the function retrieves a list of all existing MS-DOS device names. Each null-terminated string stored into the buffer is the name of an existing MS-DOS device, for example, `\Device\HarddiskVolume1` or `\Device\Floppy0`.</dd><dt>maxChars</dt><dd>Type: System.UInt32<br />The maximum number of characters that can be stored into the buffer pointed to by *targetPath*.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the number of characters stored into the buffer pointed to by *targetPath*. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error(). 

 If the buffer is too small, the function fails and the last error code is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INSUFFICIENT_BUFFER</a>.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa365461(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa365461(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_QueryDosDevice">QueryDosDevice Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />