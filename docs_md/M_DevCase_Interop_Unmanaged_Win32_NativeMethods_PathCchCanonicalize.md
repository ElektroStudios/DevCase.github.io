# NativeMethods.PathCchCanonicalize Method 
 

Converts a path string into a canonical form. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalizeEx">PathCchCanonicalizeEx(StringBuilder, UInt32, String, PathOptions)</a> in that you are restricted to a final path of length MAX_PATH. 

 This function differs from PathAllocCanonicalize in that the caller must declare the size of the returned string, which is stored on the stack. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCanonicalize">PathCanonicalize(StringBuilder, String)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchCanonicalizeEx">PathCchCanonicalizeEx(StringBuilder, UInt32, String, PathOptions)</a>, or PathAllocCanonicalize should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCanonicalize">PathCanonicalize(StringBuilder, String)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchCanonicalize(
	StringBuilder pathOut,
	uint pathOutSize,
	string pathIn
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchCanonicalize ( 
	pathOut As StringBuilder,
	pathOutSize As UInteger,
	pathIn As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim pathOut As StringBuilder
Dim pathOutSize As UInteger
Dim pathIn As String
Dim returnValue As HResult

returnValue = NativeMethods.PathCchCanonicalize(pathOut, 
	pathOutSize, pathIn)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchCanonicalize(
	StringBuilder^ pathOut, 
	unsigned int pathOutSize, 
	String^ pathIn
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchCanonicalize : 
        pathOut : StringBuilder * 
        pathOutSize : uint32 * 
        pathIn : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pathOut</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, when this function returns successfully, receives the edited path string.</dd><dt>pathOutSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *pathOut*, in characters.</dd><dt>pathIn</dt><dd>Type: System.String<br />A pointer to the original path string. 

 If this value is NULL, points to an empty string, or results in an empty string once the "." and ".." elements are removed, a single backslash is copied to the buffer pointed to by *pathOut*.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if succeed, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> failure code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcanonicalize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchcanonicalize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />