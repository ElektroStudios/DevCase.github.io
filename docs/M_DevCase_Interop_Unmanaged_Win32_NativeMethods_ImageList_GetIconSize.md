# NativeMethods.ImageList_GetIconSize Method 
 

Retrieves the dimensions of images in an image list. 

 All images in an image list have the same dimensions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll")]
public static bool ImageList_GetIconSize(
	IntPtr hImageList,
	ref int refWidth,
	ref int refHeight
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll">]
Public Shared Function ImageList_GetIconSize ( 
	hImageList As IntPtr,
	ByRef refWidth As Integer,
	ByRef refHeight As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim refWidth As Integer
Dim refHeight As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.ImageList_GetIconSize(hImageList, 
	refWidth, refHeight)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll")]
static bool ImageList_GetIconSize(
	IntPtr hImageList, 
	int% refWidth, 
	int% refHeight
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll")>]
static member ImageList_GetIconSize : 
        hImageList : IntPtr * 
        refWidth : int byref * 
        refHeight : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list.</dd><dt>refWidth</dt><dd>Type: System.Int32<br />The width, in pixels, of each image.</dd><dt>refHeight</dt><dd>Type: System.Int32<br />The height, in pixels, of each image.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); otherwise, it returns `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_geticonsize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_geticonsize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />