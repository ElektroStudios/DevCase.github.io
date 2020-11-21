# NativeMethods.SHDefExtractIcon Method 
 

Provides a default handler to extract an icon from a file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult SHDefExtractIcon(
	string iconFile,
	int iconIndex,
	uint flags,
	ref IntPtr refHiconLarge,
	ref IntPtr refHiconSmall,
	uint iconSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function SHDefExtractIcon ( 
	iconFile As String,
	iconIndex As Integer,
	flags As UInteger,
	ByRef refHiconLarge As IntPtr,
	ByRef refHiconSmall As IntPtr,
	iconSize As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim iconFile As String
Dim iconIndex As Integer
Dim flags As UInteger
Dim refHiconLarge As IntPtr
Dim refHiconSmall As IntPtr
Dim iconSize As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.SHDefExtractIcon(iconFile, 
	iconIndex, flags, refHiconLarge, 
	refHiconSmall, iconSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult SHDefExtractIcon(
	String^ iconFile, 
	int iconIndex, 
	unsigned int flags, 
	IntPtr% refHiconLarge, 
	IntPtr% refHiconSmall, 
	unsigned int iconSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member SHDefExtractIcon : 
        iconFile : string * 
        iconIndex : int * 
        flags : uint32 * 
        refHiconLarge : IntPtr byref * 
        refHiconSmall : IntPtr byref * 
        iconSize : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>iconFile</dt><dd>Type: System.String<br />A pointer to a null-terminated buffer that contains the path and name of the file from which the icon is extracted.</dd><dt>iconIndex</dt><dd>Type: System.Int32<br />The location of the icon within the file named in pszIconFile. 

 If this is a positive number, it refers to the zero-based position of the icon in the file. 

 For instance, 0 refers to the 1st icon in the resource file and 2 refers to the 3rd. If this is a negative number, it refers to the icon's resource ID.</dd><dt>flags</dt><dd>Type: System.UInt32<br />A flag that controls the icon extraction.</dd><dt>refHiconLarge</dt><dd>Type: System.IntPtr<br />A pointer to an `HICON` that, when this function returns successfully, receives the handle of the large version of the icon specified in the LOWORD of nIconSize. 

 This value can be Zero.</dd><dt>refHiconSmall</dt><dd>Type: System.IntPtr<br />A pointer to an `HICON` that, when this function returns successfully, receives the handle of the small version of the icon specified in the `HIWORD` of *iconSize* param. 

 This value can be Zero.</dd><dt>iconSize</dt><dd>Type: System.UInt32<br />A value that contains the large icon size in its `LOWORD` and the small icon size in its `HIWORD`. 

 Size is measured in pixels. 

 Pass `0` to specify default large and small sizes.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />This function can return one of these values: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_FAIL</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762149%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762149%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />