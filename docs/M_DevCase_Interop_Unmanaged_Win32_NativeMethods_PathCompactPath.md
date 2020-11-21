# NativeMethods.PathCompactPath Method 
 

Truncates a file path to fit within a given pixel width by replacing path components with ellipses.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathCompactPath(
	IntPtr hDC,
	StringBuilder path,
	uint width
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathCompactPath ( 
	hDC As IntPtr,
	path As StringBuilder,
	width As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDC As IntPtr
Dim path As StringBuilder
Dim width As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.PathCompactPath(hDC, 
	path, width)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathCompactPath(
	IntPtr hDC, 
	StringBuilder^ path, 
	unsigned int width
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathCompactPath : 
        hDC : IntPtr * 
        path : StringBuilder * 
        width : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDC</dt><dd>Type: System.IntPtr<br />A handle to the device context used for font metrics. This value can be NULL.</dd><dt>path</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a null-terminated string of length MAX_PATH that contains the path to be modified. On return, this buffer will contain the modified string.</dd><dt>width</dt><dd>Type: System.UInt32<br />The width, in pixels, in which the string must fit.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the path was successfully compacted to the specified width. 

 Returns `false` (`False` in Visual Basic) on failure, or if the base portion of the path would not fit the specified width.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcompactpatha" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlwapi/nf-shlwapi-pathcompactpatha</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />