# NativeMethods.PathResolve Method 
 

Converts a relative or unqualified path name to a fully qualified path name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathResolve(
	StringBuilder path,
	string[] dirs,
	PathResolveFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathResolve ( 
	path As StringBuilder,
	dirs As String(),
	flags As PathResolveFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As StringBuilder
Dim dirs As String()
Dim flags As PathResolveFlags
Dim returnValue As Boolean

returnValue = NativeMethods.PathResolve(path, 
	dirs, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathResolve(
	StringBuilder^ path, 
	array<String^>^ dirs, 
	PathResolveFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathResolve : 
        path : StringBuilder * 
        dirs : string[] * 
        flags : PathResolveFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A null-terminated Unicode string that contains the path to resolve. 

 When the function returns, the string contains the corresponding fully qualified path. This buffer should be at least MAX_PATH characters long.</dd><dt>dirs</dt><dd>Type: System.String[]<br />A pointer to an optional null-terminated array of directories to be searched first in the case that the path cannot be resolved from *path*. This value can be NULL.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PathResolveFlags">DevCase.Interop.Unmanaged.Win32.Enums.PathResolveFlags</a><br />Flags that specify how the function operates.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic), unless <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PathResolveFlags">VerifyExists</a> is set. If that flag is set, the function returns `true` (`True` in Visual Basic) if the file is verified to exist, and `false` (`False` in Visual Basic) otherwise. 

 It also sets an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_FILE_NOT_FOUND</a> error code that you can retrieve by calling GetLastError.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathresolve" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-pathresolve</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />