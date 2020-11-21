# NativeMethods.PathCchCombineEx Method 
 

Combines two path fragments into a single path. This function also canonicalizes any relative path elements, removing "." and ".." elements to simplify the final path. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCombine">PathCchCombine(StringBuilder, UInt32, String, String)</a> in that it allows for a longer final path to be constructed. 

 This function differs from PathAllocCombine in that the caller must declare the size of the returned string, which is stored on the stack. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCombine">PathCombine(StringBuilder, String, String)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCombine">PathCchCombine(StringBuilder, UInt32, String, String)</a>, or PathAllocCombine should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCombine">PathCombine(StringBuilder, String, String)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchCombineEx(
	StringBuilder pathOut,
	uint pathOutSize,
	string pathIn,
	string more,
	PathOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchCombineEx ( 
	pathOut As StringBuilder,
	pathOutSize As UInteger,
	pathIn As String,
	more As String,
	flags As PathOptions
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pathOut As StringBuilder
Dim pathOutSize As UInteger
Dim pathIn As String
Dim more As String
Dim flags As PathOptions
Dim returnValue As HResult

returnValue = NativeMethods.PathCchCombineEx(pathOut, 
	pathOutSize, pathIn, more, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchCombineEx(
	StringBuilder^ pathOut, 
	unsigned int pathOutSize, 
	String^ pathIn, 
	String^ more, 
	PathOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchCombineEx : 
        pathOut : StringBuilder * 
        pathOutSize : uint32 * 
        pathIn : string * 
        more : string * 
        flags : PathOptions -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pathOut</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the combined path string. 

 This parameter can point to the same buffer as *pathIn* or *more*.</dd><dt>pathOutSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *pathOut*, in characters.</dd><dt>pathIn</dt><dd>Type: System.String<br />A pointer to the first path string. 

 This value can be NULL.</dd><dt>more</dt><dd>Type: System.String<br />A pointer to the second path string. 

 If this path begins with a single backslash, it is combined with only the root of the path pointed to by *pathIn*. 

 If this path is fully qualfied, it is copied directly to the output buffer without being combined with the other path. 

 This value can be NULL.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PathOptions">DevCase.Interop.Unmanaged.Win32.Enums.PathOptions</a><br />Flags that determine how to combine the path.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if succeed, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> failure code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcombineex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcombineex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />