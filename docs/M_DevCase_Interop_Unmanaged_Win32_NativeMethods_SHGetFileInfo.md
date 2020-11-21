# NativeMethods.SHGetFileInfo Method (IntPtr, FileAttributes, ShellFileInfo, UInt32, SHGetFileInfoFlags)
 

Retrieves information about an object in the file system, such as a file, folder, directory, or drive root.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static IntPtr SHGetFileInfo(
	IntPtr pidl,
	FileAttributes fileAttribs,
	ref ShellFileInfo refShellFileInfo,
	uint size,
	SHGetFileInfoFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function SHGetFileInfo ( 
	pidl As IntPtr,
	fileAttribs As FileAttributes,
	ByRef refShellFileInfo As ShellFileInfo,
	size As UInteger,
	flags As SHGetFileInfoFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pidl As IntPtr
Dim fileAttribs As FileAttributes
Dim refShellFileInfo As ShellFileInfo
Dim size As UInteger
Dim flags As SHGetFileInfoFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.SHGetFileInfo(pidl, 
	fileAttribs, refShellFileInfo, size, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static IntPtr SHGetFileInfo(
	IntPtr pidl, 
	FileAttributes fileAttribs, 
	ShellFileInfo% refShellFileInfo, 
	unsigned int size, 
	SHGetFileInfoFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member SHGetFileInfo : 
        pidl : IntPtr * 
        fileAttribs : FileAttributes * 
        refShellFileInfo : ShellFileInfo byref * 
        size : uint32 * 
        flags : SHGetFileInfoFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />A pointer to a null-terminated string of maximum length `MAX_PATH` that contains the path and file name. Both absolute and relative paths are valid. 

 If the *flags* parameter includes the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">PIDL</a> flag, this parameter must be the address of an `ITEMIDLIST` (`PIDL`) structure that contains the list of item identifiers that uniquely identifies the file within the Shell's namespace. The `PIDL` must be a fully qualified `PIDL`. Relative `PIDLs` are not allowed. 

 If the *flags* parameter includes the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">UseFileAttributes</a> flag, this parameter does not have to be a valid file name. The function will proceed as if the file exists with the specified name and with the file attributes passed in the *fileAttribs* parameter. This allows you to obtain information about a file type by passing just the extension for *pidl* parameter and passing FILE_ATTRIBUTE_NORMAL in *fileAttribs* parameter</dd><dt>fileAttribs</dt><dd>Type: System.IO.FileAttributes<br />A combination of one or more file attribute flags. 

 If *flags* parameter does not include the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">UseFileAttributes</a> flag, this parameter is ignored.</dd><dt>refShellFileInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">DevCase.Interop.Unmanaged.Win32.Structures.ShellFileInfo</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">ShellFileInfo</a> structure to receive the file information.</dd><dt>size</dt><dd>Type: System.UInt32<br />The size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellFileInfo">ShellFileInfo</a> structure pointed to by the *refShellFileInfo* parameter.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHGetFileInfoFlags</a><br />The flags that specify the file information to retrieve.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns a value whose meaning depends on the *flags* parameter. 

 If *flags* parameter does not contain <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">ExeType</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">SysIconIndex</a>, the return value is nonzero if successful, or zero otherwise. 

 If *flags* parameter contains the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetFileInfoFlags">ExeType</a> flag, the return value specifies the type of the executable.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/bb762179(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/bb762179(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetFileInfo">SHGetFileInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />