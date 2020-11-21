# NativeMethods.ImageList_GetIcon Method 
 

Creates an icon from an image and mask in an image list.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll")]
public static IntPtr ImageList_GetIcon(
	IntPtr hImageList,
	int index,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll">]
Public Shared Function ImageList_GetIcon ( 
	hImageList As IntPtr,
	index As Integer,
	flags As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim index As Integer
Dim flags As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.ImageList_GetIcon(hImageList, 
	index, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll")]
static IntPtr ImageList_GetIcon(
	IntPtr hImageList, 
	int index, 
	unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll")>]
static member ImageList_GetIcon : 
        hImageList : IntPtr * 
        index : int * 
        flags : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list.</dd><dt>index</dt><dd>Type: System.Int32<br />\[Missing <param name="index"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.ImageList_GetIcon(System.IntPtr,System.Int32,System.UInt32)"\]</dd><dt>flags</dt><dd>Type: System.UInt32<br />A combination of flags that specify the drawing style.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the handle to the icon if successful, or Zero otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_geticon" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_geticon</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />