# NativeMethods.DeleteFile Method 
 

Deletes an existing file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool DeleteFile(
	string filepath
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function DeleteFile ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteFile(filepath)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool DeleteFile(
	String^ filepath
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member DeleteFile : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The path of the file to be deleted. 

 In the `ANSI` version of this function (DeleteFileA), the name is limited to `MAX_PATH` characters. To extend this limit to `32,767` wide characters, call the `Unicode` version of the function (DeleteFileW) and prepend "`\\?\`" to the path, for example: `DeleteFileW("\\?\C:\Very Long Path\File.ext")`</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa363915%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa363915%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />