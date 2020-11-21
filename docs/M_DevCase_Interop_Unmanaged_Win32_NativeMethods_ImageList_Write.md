# NativeMethods.ImageList_Write Method 
 

Writes an image list to a stream.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", SetLastError = true)]
public static bool ImageList_Write(
	IntPtr hImageList,
	IStream stream
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", SetLastError := true>]
Public Shared Function ImageList_Write ( 
	hImageList As IntPtr,
	stream As IStream
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hImageList As IntPtr
Dim stream As IStream
Dim returnValue As Boolean

returnValue = NativeMethods.ImageList_Write(hImageList, 
	stream)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", SetLastError = true)]
static bool ImageList_Write(
	IntPtr hImageList, 
	IStream^ stream
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", SetLastError = true)>]
static member ImageList_Write : 
        hImageList : IntPtr * 
        stream : IStream -> bool 

```


#### Parameters
&nbsp;<dl><dt>hImageList</dt><dd>Type: System.IntPtr<br />A handle to the image list.</dd><dt>stream</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IStream<br />The stream.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_write" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_write</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />