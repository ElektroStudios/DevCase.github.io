# NativeMethods.PathCchCanonicalizeEx Method 
 

Simplifies a path by removing navigation elements such as "." and ".." to produce a direct, well-formed path. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalize">PathCchCanonicalize(StringBuilder, UInt32, String)</a> in that it allows for a longer final path to be constructed. 

 This function differs from PathAllocCanonicalize in that the caller must declare the size of the returned string, which is stored on the stack. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCanonicalize">PathCanonicalize(StringBuilder, String)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalize">PathCchCanonicalize(StringBuilder, UInt32, String)</a>, or PathAllocCanonicalize should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCanonicalize">PathCanonicalize(StringBuilder, String)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchCanonicalizeEx(
	StringBuilder pathOut,
	uint pathOutSize,
	string pathIn,
	PathOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchCanonicalizeEx ( 
	pathOut As StringBuilder,
	pathOutSize As UInteger,
	pathIn As String,
	flags As PathOptions
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pathOut As StringBuilder
Dim pathOutSize As UInteger
Dim pathIn As String
Dim flags As PathOptions
Dim returnValue As HResult

returnValue = NativeMethods.PathCchCanonicalizeEx(pathOut, 
	pathOutSize, pathIn, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchCanonicalizeEx(
	StringBuilder^ pathOut, 
	unsigned int pathOutSize, 
	String^ pathIn, 
	PathOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchCanonicalizeEx : 
        pathOut : StringBuilder * 
        pathOutSize : uint32 * 
        pathIn : string * 
        flags : PathOptions -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pathOut</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the edited path string.</dd><dt>pathOutSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *pathOut*, in characters.</dd><dt>pathIn</dt><dd>Type: System.String<br />A pointer to the original path string. 

 If this value is NULL, points to an empty string, or results in an empty string once the "." and ".." elements are removed, a single backslash is copied to the buffer pointed to by *pathOut*.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PathOptions">DevCase.Interop.Unmanaged.Win32.Enums.PathOptions</a><br />Flags that determine how to canonicalize the path.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if succeed, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> failure code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcanonicalizeex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcanonicalizeex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />