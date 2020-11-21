# NativeMethods.DeleteEnhMetaFile Method 
 

Deletes an enhanced-format metafile or an enhanced-format metafile handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static bool DeleteEnhMetaFile(
	IntPtr hMetafile
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function DeleteEnhMetaFile ( 
	hMetafile As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMetafile As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteEnhMetaFile(hMetafile)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static bool DeleteEnhMetaFile(
	IntPtr hMetafile
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member DeleteEnhMetaFile : 
        hMetafile : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMetafile</dt><dd>Type: System.IntPtr<br />A handle to an enhanced metafile.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-deleteenhmetafile" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-deleteenhmetafile</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />