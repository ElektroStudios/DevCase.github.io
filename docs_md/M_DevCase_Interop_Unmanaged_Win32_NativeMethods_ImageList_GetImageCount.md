# NativeMethods.ImageList_GetImageCount Method 
 

Retrieves the number of images in an image list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll")]
public static int ImageList_GetImageCount(
	IntPtr hImageList
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll">]
Public Shared Function ImageList_GetImageCount ( 
	hImageList As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.ImageList_GetImageCount(hImageList)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll")]
static int ImageList_GetImageCount(
	IntPtr hImageList
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll")>]
static member ImageList_GetImageCount : 
        hImageList : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list.</dd></dl>

#### Return Value
Type: Int32<br />Returns the number of images.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_getimagecount" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_getimagecount</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />