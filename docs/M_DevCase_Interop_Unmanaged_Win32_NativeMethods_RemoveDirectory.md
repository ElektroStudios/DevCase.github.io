# NativeMethods.RemoveDirectory Method 
 

Deletes an existing empty directory.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool RemoveDirectory(
	string pathName
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function RemoveDirectory ( 
	pathName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim pathName As String
Dim returnValue As Boolean

returnValue = NativeMethods.RemoveDirectory(pathName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool RemoveDirectory(
	String^ pathName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member RemoveDirectory : 
        pathName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>pathName</dt><dd>Type: System.String<br />The path of the directory to be removed. This path must specify an empty directory, and the calling process must have delete access to the directory. 

 In the ANSI version of this function, the name is limited to `MAX_PATH` characters. To extend this limit to 32,767 wide characters, call the Unicode version of the function and prepend "\\?\" to the path.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-removedirectorya" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/fileapi/nf-fileapi-removedirectorya</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />