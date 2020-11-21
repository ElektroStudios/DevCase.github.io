# NativeMethods.PathCompactPathEx Method 
 

Truncates a path to fit within a certain number of characters by replacing path components with ellipses.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathCompactPathEx(
	StringBuilder buffer,
	string sourcePath,
	uint width,
	uint flags = 0
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathCompactPathEx ( 
	buffer As StringBuilder,
	sourcePath As String,
	width As UInteger,
	Optional flags As UInteger = 0
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim sourcePath As String
Dim width As UInteger
Dim flags As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PathCompactPathEx(buffer, 
	sourcePath, width, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathCompactPathEx(
	StringBuilder^ buffer, 
	String^ sourcePath, 
	unsigned int width, 
	unsigned int flags = 0
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathCompactPathEx : 
        buffer : StringBuilder * 
        sourcePath : string * 
        width : uint32 * 
        ?flags : uint32 
(* Defaults:
        let _flags = defaultArg flags 0
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />The address of the string that has been altered.</dd><dt>sourcePath</dt><dd>Type: System.String<br />A pointer to a null-terminated string of length MAX_PATH that contains the path to be altered.</dd><dt>width</dt><dd>Type: System.UInt32<br />The maximum number of characters to be contained in the new string, including the terminating null character. 

 For example, if *width* = 8, the resulting string can contain a maximum of 7 characters plus the terminating null character.</dd><dt>flags (Optional)</dt><dd>Type: System.UInt32<br />(NOT DOCUMENTED).</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcompactpathexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcompactpathexa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />