# NativeMethods.CreateDirectory Method 
 

Creates a new directory. 

 If the underlying file system supports security on files and directories, the function applies a specified security descriptor to the new directory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool CreateDirectory(
	string dirpath,
	IntPtr securityAttributes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateDirectory ( 
	dirpath As String,
	securityAttributes As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim dirpath As String
Dim securityAttributes As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.CreateDirectory(dirpath, 
	securityAttributes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool CreateDirectory(
	String^ dirpath, 
	IntPtr securityAttributes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateDirectory : 
        dirpath : string * 
        securityAttributes : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>dirpath</dt><dd>Type: System.String<br />The path of the directory to be created. 

 In the `ANSI` version of this function (<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateDirectoryA">CreateDirectoryA(String, IntPtr)</a>), there is a default string size limit for paths of `248` characters. To extend this limit to `32,767` wide characters, call the `Unicode` version of the function (<a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateDirectoryW">CreateDirectoryW(String, IntPtr)</a>) and prepend "`\\?\`" to the path, for example: `CreateDirectoryW("\\?\C:\Very Long Path")`</dd><dt>securityAttributes</dt><dd>Type: System.IntPtr<br />A pointer to a `SECURITY_ATTRIBUTES` structure. 

 The `SecurityDescriptor` member of the structure specifies a security descriptor for the new directory. 

 If *SecurityAttributes* is Zero, the directory gets a default security descriptor. 

 The `ACL`s in the default security descriptor for a directory are inherited from its parent directory.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa363855%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa363855%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />