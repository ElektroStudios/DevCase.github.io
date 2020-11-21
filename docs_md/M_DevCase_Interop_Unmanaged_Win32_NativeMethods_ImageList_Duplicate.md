# NativeMethods.ImageList_Duplicate Method 
 

Creates a duplicate of an existing image list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll")]
public static IntPtr ImageList_Duplicate(
	IntPtr hImageList
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll">]
Public Shared Function ImageList_Duplicate ( 
	hImageList As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.ImageList_Duplicate(hImageList)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll")]
static IntPtr ImageList_Duplicate(
	IntPtr hImageList
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll")>]
static member ImageList_Duplicate : 
        hImageList : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list to be duplicated. 

 All information contained in the original image list for normal images is copied to the new image list. Overlay images are not copied.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the handle to the new duplicate image list if successful, or Zero otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_duplicate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_duplicate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />