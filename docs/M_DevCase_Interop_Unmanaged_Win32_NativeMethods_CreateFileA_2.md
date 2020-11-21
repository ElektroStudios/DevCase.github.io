# NativeMethods.CreateFileA Method (String, FileAccessRights, FileShare, IntPtr, FileMode, UInt32, IntPtr)
 

Creates or opens a file or I/O device. 

 The most commonly used I/O devices are as follows: 

 file, file stream, directory, physical disk, volume, console buffer, tape drive, communications resource, mailslot, and pipe. 

 The function returns a handle that can be used to access the file or device for various types of I/O depending on the file or device and the flags and attributes specified.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static SafeFileHandle CreateFileA(
	string filepath,
	FileAccessRights access,
	FileShare share,
	IntPtr securityAttributes,
	FileMode creationDisposition,
	uint flagsAndAttributes,
	IntPtr templateFile
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Ansi, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateFileA ( 
	filepath As String,
	access As FileAccessRights,
	share As FileShare,
	securityAttributes As IntPtr,
	creationDisposition As FileMode,
	flagsAndAttributes As UInteger,
	templateFile As IntPtr
) As SafeFileHandle
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim access As FileAccessRights
Dim share As FileShare
Dim securityAttributes As IntPtr
Dim creationDisposition As FileMode
Dim flagsAndAttributes As UInteger
Dim templateFile As IntPtr
Dim returnValue As SafeFileHandle

returnValue = NativeMethods.CreateFileA(filepath, 
	access, share, securityAttributes, 
	creationDisposition, flagsAndAttributes, 
	templateFile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static SafeFileHandle^ CreateFileA(
	String^ filepath, 
	FileAccessRights access, 
	FileShare share, 
	IntPtr securityAttributes, 
	FileMode creationDisposition, 
	unsigned int flagsAndAttributes, 
	IntPtr templateFile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Ansi, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateFileA : 
        filepath : string * 
        access : FileAccessRights * 
        share : FileShare * 
        securityAttributes : IntPtr * 
        creationDisposition : FileMode * 
        flagsAndAttributes : uint32 * 
        templateFile : IntPtr -> SafeFileHandle 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The name of the file or device to be created or opened. 

 In the `ANSI` version of this function (<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFileA">CreateFileA(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a>), the name is limited to `MAX_PATH` characters. To extend this limit to `32,767` wide characters, call the `Unicode` version of the function (<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFileW">CreateFileW(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a>) and prepend "`\\?\`" to the path, for example: `CreateFileW("\\?\C:\Very Long Path\File.txt")`</dd><dt>access</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_FileAccessRights">DevCase.Interop.Unmanaged.Win32.Enums.FileAccessRights</a><br />The requested access to the file or device, which can be summarized as read, write, both or neither zero.</dd><dt>share</dt><dd>Type: System.IO.FileShare<br />The requested sharing mode of the file or device, which can be read, write, both, delete, all of these, or none (refer to the following table). 

 Access requests to attributes or extended attributes are not affected by this flag.</dd><dt>securityAttributes</dt><dd>Type: System.IntPtr<br />A pointer to a `SECURITY_ATTRIBUTES` structure that contains two separate but related data members: an optional security descriptor, and a Boolean value that determines whether the returned handle can be inherited by child processes.</dd><dt>creationDisposition</dt><dd>Type: System.IO.FileMode<br />An action to take on a file or device that exists or does not exist.</dd><dt>flagsAndAttributes</dt><dd>Type: System.UInt32<br />The file or device attributes and flags.</dd><dt>templateFile</dt><dd>Type: System.IntPtr<br />A valid handle to a template file with the GENERIC_READ access right. 

 The template file supplies file attributes and extended attributes for the file that is being created.</dd></dl>

#### Return Value
Type: SafeFileHandle<br />If the function succeeds, the return value is an open handle to the specified file, device, named pipe, or mail slot. 

 If the function fails, the return value is a `INVALID_HANDLE_VALUE` value (`IntPtr(-1)`). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363858%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363858%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFileA">CreateFileA Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />