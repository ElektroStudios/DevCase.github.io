# NativeMethods.CreateEnhMetaFile Method (IntPtr, String, NativeRectangle, String)
 

Creates a device context (DC) for an enhanced-format metafile. 

 This device context can be used to store a device-independent picture.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr CreateEnhMetaFile(
	IntPtr hDc,
	string filename,
	ref NativeRectangle refRect,
	string description
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateEnhMetaFile ( 
	hDc As IntPtr,
	filename As String,
	ByRef refRect As NativeRectangle,
	description As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hDc As IntPtr
Dim filename As String
Dim refRect As NativeRectangle
Dim description As String
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateEnhMetaFile(hDc, 
	filename, refRect, description)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr CreateEnhMetaFile(
	IntPtr hDc, 
	String^ filename, 
	NativeRectangle% refRect, 
	String^ description
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateEnhMetaFile : 
        hDc : IntPtr * 
        filename : string * 
        refRect : NativeRectangle byref * 
        description : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hDc</dt><dd>Type: System.IntPtr<br />A handle to a reference device for the enhanced metafile. 

 This parameter can be Zero.</dd><dt>filename</dt><dd>Type: System.String<br />The file name for the enhanced metafile to be created. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the enhanced metafile is memory based and its contents are lost when it is deleted by using the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteEnhMetaFile">DeleteEnhMetaFile(IntPtr)</a> function.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the dimensions (in .01-millimeter units) of the picture to be stored in the enhanced metafile.</dd><dt>description</dt><dd>Type: System.String<br />A string that specifies the name of the application that created the picture, as well as the picture's title. 

 This parameter can be a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the device context for the enhanced metafile. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createenhmetafilea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-createenhmetafilea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateEnhMetaFile">CreateEnhMetaFile Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />