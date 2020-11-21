# NativeMethods.CreateHardLink Method (String, String, IntPtr)
 

Establishes a hard link between an existing file and a new file. 

 This function is only supported on the NTFS file system, and only for files, not directories.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool CreateHardLink(
	string dstFilePath,
	string srcFilePath,
	IntPtr reserved = null
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateHardLink ( 
	dstFilePath As String,
	srcFilePath As String,
	Optional reserved As IntPtr = Nothing
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim dstFilePath As String
Dim srcFilePath As String
Dim reserved As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.CreateHardLink(dstFilePath, 
	srcFilePath, reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool CreateHardLink(
	String^ dstFilePath, 
	String^ srcFilePath, 
	IntPtr reserved = nullptr
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateHardLink : 
        dstFilePath : string * 
        srcFilePath : string * 
        ?reserved : IntPtr 
(* Defaults:
        let _reserved = defaultArg reserved null
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>dstFilePath</dt><dd>Type: System.String<br />The name of the new file. 

 This parameter may include the path but cannot specify the name of a directory.</dd><dt>srcFilePath</dt><dd>Type: System.String<br />The name of the existing file. 

 This parameter may include the path cannot specify the name of a directory.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved; must be Zero.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 The maximum number of hard links that can be created with this function is 1023 per file. If more than 1023 links are created for a file, an error results. 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createhardlinka" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createhardlinka</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateHardLink">CreateHardLink Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />