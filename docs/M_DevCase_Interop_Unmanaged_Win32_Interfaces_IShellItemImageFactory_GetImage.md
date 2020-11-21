# IShellItemImageFactory.GetImage Method 
 

Gets an HBITMAP that represents an IShellItem. The default behavior is to load a thumbnail. If there is no thumbnail for the current IShellItem, it retrieves an HBITMAP for the icon of the item. The thumbnail or icon is extracted if it is not currently cached.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetImage(
	Size size,
	IShellItemImageFactoryGetImageFlags flags,
	ref IntPtr phbm
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetImage ( 
	size As Size,
	flags As IShellItemImageFactoryGetImageFlags,
	ByRef phbm As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItemImageFactory
Dim size As Size
Dim flags As IShellItemImageFactoryGetImageFlags
Dim phbm As IntPtr
Dim returnValue As HResult

returnValue = instance.GetImage(size, 
	flags, phbm)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetImage(
	[InAttribute] Size size, 
	[InAttribute] IShellItemImageFactoryGetImageFlags flags, 
	IntPtr% phbm
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetImage : 
        size : Size * 
        flags : IShellItemImageFactoryGetImageFlags * 
        phbm : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Drawing.Size<br />A structure that specifies the size of the image to be received.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellItemImageFactoryGetImageFlags">DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags</a><br />One or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_IShellItemImageFactoryGetImageFlags">IShellItemImageFactoryGetImageFlags</a> flags.</dd><dt>phbm</dt><dd>Type: System.IntPtr<br />Pointer to a value that, when this method returns successfully, receives the handle of the retrieved bitmap. 

 It is the responsibility of the caller to free this retrieved resource through <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteObject">DeleteObject(IntPtr)</a> function when it is no longer needed.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory">IShellItemImageFactory Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />