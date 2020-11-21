# NativeMethods.ImageList_Destroy Method 
 

Destroys an image list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll")]
public static bool ImageList_Destroy(
	IntPtr hImageList
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll">]
Public Shared Function ImageList_Destroy ( 
	hImageList As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ImageList_Destroy(hImageList)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll")]
static bool ImageList_Destroy(
	IntPtr hImageList
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll")>]
static member ImageList_Destroy : 
        hImageList : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list to destroy.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic); otherwise, it returns `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_destroy" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_destroy</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />