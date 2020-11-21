# NativeMethods.ImageList_Read Method 
 

Reads an image list from a stream.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ComCtl32.dll", SetLastError = true)]
public static IntPtr ImageList_Read(
	IStream stream
)
```

**VB**<br />
``` VB
<DllImportAttribute("ComCtl32.dll", SetLastError := true>]
Public Shared Function ImageList_Read ( 
	stream As IStream
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim stream As IStream
Dim returnValue As IntPtr

returnValue = NativeMethods.ImageList_Read(stream)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ComCtl32.dll", SetLastError = true)]
static IntPtr ImageList_Read(
	IStream^ stream
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ComCtl32.dll", SetLastError = true)>]
static member ImageList_Read : 
        stream : IStream -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>stream</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IStream<br />A pointer to the stream.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the handle to the image list if successful, or Zero otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_read" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/commctrl/nf-commctrl-imagelist_read</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />