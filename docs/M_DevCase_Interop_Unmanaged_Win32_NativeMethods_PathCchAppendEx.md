# NativeMethods.PathCchAppendEx Method 
 

Appends one path to the end of another. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAppend">PathCchAppend(StringBuilder, UInt32, String)</a> in that it allows for a longer final path to be constructed. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAppend">PathAppend(StringBuilder, String)</a> in that it accepts paths with "\", "\?" and "\?\UNC" prefixes. 

 Note: This function, or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCchAppend">PathCchAppend(StringBuilder, UInt32, String)</a>, should be used in place of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathAppend">PathAppend(StringBuilder, String)</a> to prevent the possibility of a buffer overrun.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult PathCchAppendEx(
	StringBuilder buffer,
	uint bufferSize,
	string more,
	PathOptions flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function PathCchAppendEx ( 
	buffer As StringBuilder,
	bufferSize As UInteger,
	more As String,
	flags As PathOptions
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim buffer As StringBuilder
Dim bufferSize As UInteger
Dim more As String
Dim flags As PathOptions
Dim returnValue As HResult

returnValue = NativeMethods.PathCchAppendEx(buffer, 
	bufferSize, more, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult PathCchAppendEx(
	StringBuilder^ buffer, 
	unsigned int bufferSize, 
	String^ more, 
	PathOptions flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member PathCchAppendEx : 
        buffer : StringBuilder * 
        bufferSize : uint32 * 
        more : string * 
        flags : PathOptions -> HResult 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a buffer that, on entry, contains the original path. 

 When this function returns successfully, the buffer contains the original path plus the appended path.</dd><dt>bufferSize</dt><dd>Type: System.UInt32<br />The size of the buffer pointed to by *buffer*, in characters.</dd><dt>more</dt><dd>Type: System.String<br />A pointer the path to append to the end of the path pointed to by pszPath. 

 UNC paths and paths that begin with the sequence \?\ are accepted and recognized as fully-qualified paths. These paths replace the string pointed to by *buffer* instead of being appended to it.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PathOptions">DevCase.Interop.Unmanaged.Win32.Enums.PathOptions</a><br />Flags that determine how to append the path.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchappendex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathcchappendex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />